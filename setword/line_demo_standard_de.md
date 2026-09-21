---

layout: default
title: "Swatch-Simulator"
lang: de
---



## Referenzwert



### Datenreferenzhinweis

Die bereitgestellten Daten dienen nur als Referenz. Aufgrund von Unterschieden in der Spannung und den Nähmustern der Stricker kann die Dichte der Muster auch bei Verwendung derselben Garn- und Nadelgröße variieren. Daher wird empfohlen, beim Handstricken zunächst ein Muster zu stricken, zu waschen und zu blockieren, dann die tatsächliche Dichte zu messen, um die endgültige Anzahl der Maschen und Reihen für das Projekt zu bestimmen, wobei Abweichungen in der fertigen Produktgröße vermieden werden.



### Ich. Kernziel

Implementieren Sie aus der Programmierperspektive einen **rasterbasierten Strick-/Häkelmustersimulator**, mit dem Hauptziel, **physische Garnparameter auf visuelle Gitterparameter abzubilden, wobei jeder Stich einer Gitterzelle abgebildet ist**.



#### Technischer Kernworkflow

```

Eingabeparameter (Garndurchmesser/Anzahl/Fachung usw.) → Berechnen Sie die Standardlehre (Stiche/Reihen pro 10 cm) → Konvertieren Sie in Rasterreihen/-Spalten für 10 cm Muster → Passen Sie den Gitterstil an Strick-/Häkeltechniken an → Rendern Sie das Raster in der App

```



### II. Grundlegende Datenstandards

Alle Berechnungsformeln basieren auf den folgenden internationalen/industriellen Standards, um die Datengenauigkeit zu gewährleisten:



| Standardnummer | Standardname | Kernanwendungsszenario |

| :-------------------------------- | :-------------------------------------------- | :------------------------------------------------ |

| ISO 2314:2010 | Textilien - Bestimmung der Garnzahl | Umrechnung zwischen Garnzahl, Durchmesser und Länge |

| ASTM D2253-19 | Standardprüfmethode für Masse pro Einheit Fläche und Dichte von gestrickten Stoffen | Benchmark für die Berechnung der Stärke (Stiche/Zeihen) |

| JIS L1096:2010 | Prüfverfahren für gewebte und gestrickte Stoffe | Branchenreferenzbereich für Strick-/Häkellehre |

| IWTO (International Wool Textile Organization) Standards | Korrelation zwischen Wollgarndurchmesser und -lage | Korrektur des tatsächlichen Durchmessers basierend auf der Anzahl der Lagen |



### III. Messgerätberechnung (ASTM D2253 Standard)

Die Stärke (Stiche pro 10 cm) ist der Kern der Rasterkartierung, berechnet auf der Grundlage von **tatsächlichem Garndurchmesser + Handwerkstyp**, bezogen auf den in JIS L1096 angegebenen Dichtebereich.



| Tatsächlicher Garndurchmesser (mm) | Stricklehre (Stiche/10cm) | Häkellehre (Stiche/10cm) | Strickreihen/10cm | Häkelreihen/10cm |

| :------------------------ | :--------------------------------- | :---------------------------- | :----------------- | :----------------- |

| 0,2~0,3 | 27~32 (Feines Garn) | 25~30 | 23~26 | 18~21 |

| 0,3~0,5 | 21~26 (mittelfeines Garn) | 20~25 | 19~22 | 15~18 |

| 0,5~0,8 | 16~20 (Kerngarn) | 15~20 | 15~18 | 12~15 |

| 0,8~1,2 | 12~15 (Sperriges Garn) | 10~15 | 11~14 | 8~11 |

| >1,2 | 7~11 (super sperriges Garn) | 7~10 | 7~10 | 5~8 |



**Beispiel**: Tatsächlicher Garndurchmesser 0,25 mm (2-lagiges feines Garn) → Stricklehre = 29 Maschen/10cm → Strickreihen = 29 × 0,8 = 23,2 Reihen/10cm



#### 1. Kerndefinitionen

Stärke = **Breite Spurweite (Stiche pro 10 cm)** / **Höhenlehre (Reihen pro 10 cm)** innerhalb der angegebenen Größe (10 cm)

- Breitenlehre: Anzahl der Stiche innerhalb von 10 cm Breite (bestimmt die Breite des fertigen Produkts);

- Höhenanzeige: Anzahl der Reihen innerhalb von 10 cm Höhe (bestimmt die Länge des Endprodukts).



#### 2. Standard-Testverfahren

ASTM D2253 erfordert "Stichtstricken + standardisierte Messung", um die Genauigkeit zu gewährleisten, mit den folgenden Schritten:

1. **Stricken Sie das Muster**:

- Verwenden Sie das eigentliche Garn und die Nadeln für das Projekt, um ein Muster von mindestens 15 cm×15 cm zu stricken (um zu vermeiden, dass sich die Kantenverformung auf die Messung auswirkt);

- Das Stichmuster muss mit dem fertigen Produkt übereinstimmen (die Dichte variiert erheblich zwischen verschiedenen Stichen wie Stockinette-Stich und Brioche-Stich).

2. **Dampfblockierung (kritischer Schritt)**:

- Dampfbügeln Sie das Muster entsprechend dem Garnmaterial (Wolle/Baumwolle/Synthetikfaser) (nur Dampf, kein Pressen oder Dehnen);

- Messen Sie nach dem natürlichen Trocknen (unblockierte Muster können schrumpfen, was zu Fehlern bei der Berechnung des Messgeräts führt).

3. **Präzise Messung**:

- Horizontal: Messen Sie 10 cm im zentralen Bereich des Musters (unter Vermeidung von 2-3 cm von den Rändern) und zählen Sie die Anzahl der Maschen (fraktionierte Stiche sind erlaubt, z.B. 18,5 Maschen);

- Vertikal: Messen Sie 10 cm im selben zentralen Bereich und zählen Sie die Anzahl der Reihen;

- Wiederholen Sie die Messung 2-3 Mal und nehmen Sie den Durchschnitt (um die Genauigkeit zu verbessern).

4. **Ergebnisse berechnen**:

Beispiel: 18 Maschen horizontal und 24 Reihen vertikal innerhalb von 10 cm → Die Spurweite ist "18 Maschen × 24 Reihen / 10 cm".



### IV. Stricken vs. Häkeln

Sekundäre Stichkategorien werden einheitlich durch "Kurz/Mittel/Lang" gekennzeichnet.



| Universalstichgrad | Strickkorrelation | Häkelkorrelation | Kerndichtefunktion | Korrekturfaktor |

|:-----------------------|:----------------------------|:-----------------------|:------------------------------|:--------------------|

| Kurz | Stropfstich | Einfache Häkelarbeit (SC) | Kompakteste (Basislinie) | 1,0 |

| Mittel | Umgekehrter Stockinette-Stich | Halbe Doppelhäkelarbeit (HDC) | Mäßig locker | 0,85 |

| Lang | Brioche-Stich | Doppelhäkeln (DC) | Extrem locker | 0,7 |


