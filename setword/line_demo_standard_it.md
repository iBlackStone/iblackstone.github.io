---
Layout: predefinito
title: "Simulatore di campioni"
lang: it
---

## Valore di riferimento

### Nota di riferimento dei dati
I dati forniti sono solo di riferimento. A causa delle variazioni nella tensione e nei modelli di cucitura dei magliai, la densità dei campioni può differire anche quando si utilizza la stessa misura di filato e ago. Pertanto, per il lavoro a mano, si consiglia di lavorare prima a maglia un campione, lavarlo e bloccarlo, quindi misurare la densità effettiva per determinare il numero finale di punti e righe per il progetto, evitando deviazioni nella dimensione del prodotto finito.

### Io. Obiettivo principale
Dal punto di vista della programmazione, implementare un **simulatore di maglieria/uncinetto basato su griglia**, con l'obiettivo principale di **mappare i parametri fisici del filato ai parametri della griglia visiva, dove ogni punto è mappato su una cella a griglia**.

#### Flusso di lavoro tecnico di base
```
Parametri di input (Diametro del filo/Conteggio/Ply, ecc.) → Calcola il calibro standard (punti/righe per 10 cm) → Converti in righe/colonne della griglia per campioni di 10 cm → Adatta lo stile della griglia alle tecniche di lavoro a maglia/uncinetto → Rendi la griglia sull'app
```

### II. Standard di base dei dati
Tutte le formule di calcolo si basano sui seguenti standard internazionali/industriali per garantire l'accuratezza dei dati:

| Numero standard | Nome standard | Scenario dell'applicazione principale |
| :-------------------------------- | :-------------------------------------------- | :------------------------------------------------ |
| ISO 2314:2010 | Tessuti - Determinazione del numero di filati | Conversione tra numero di filati, diametro e lunghezza |
| ASTM D2253-19 | Metodo di prova standard per la massa per unità di superficie e la densità dei tessuti a maglia | Benchmark per il calcolo del calibro (punti/righe) |
| JIS L1096:2010 | Metodi di prova per tessuti e tessuti a maglia | Gamma di riferimento del settore per il calibro per maglieria/uncinetto |
| Standard IWTO (International Wool Textile Organization) | Correlazione tra il diametro del filato di lana e lo strato | Correzione del diametro effettivo in base al conteggio degli strati |

### III. Calcolo del calibro (standard ASTM D2253)
Il calibro (punti per 10 cm) è il nucleo della mappatura della griglia, calcolato in base al **diametro effettivo del filato + tipo di mestiere**, con riferimento all'intervallo di densità specificato in JIS L1096.

| Diametro effettivo del filato (mm) | Calibro per maglieria (punti/10cm) | Calibro all'uncinetto (punti/10cm) | File per maglieria/10cm | File all'uncinetto/10cm |
| :----------------------- | :--------------------------------- | :---------------------------- | :----------------- | :---------------- |
| 0,2~0,3 | 27~32 (filato fine) | 25~30 | 23~26 | 18~21 |
| 0,3~0,5 | 21~26 (filato medio-fine) | 20~25 | 19~22 | 15~18 |
| 0,5~0,8 | 16~20 (filato con arrive) | 15~20 | 15~18 | 12~15 |
| 0,8~1,2 | 12~15 (filato ingominante) | 10~15 | 11~14 | 8~11 |
| >1,2 | 7~11 (filato super ingombrante) | 7~10 | 7~10 | 5~8 |

**Esempio**: Diametro effettivo del filato 0,25 mm (filato fine a 2 strati) → Calibro per maglieria = 29 punti/10 cm → File per maglieria = 29 × 0,8 = 23,2 file/10 cm

#### 1. Definizioni fondamentali
Calibro = **Larghezza (Punti per 10 cm)** / **Calibro di altezza (Righe per 10 cm)** all'interno della dimensione specificata (10 cm)
- Misuratore di larghezza: numero di punti entro 10 cm di larghezza (determina la larghezza del prodotto finito);
- Indicatore di altezza: numero di file entro 10 cm di altezza (determina la lunghezza del prodotto finito).

#### 2. Procedure di test standard
ASTM D2253 richiede "swatch knitting + misurazione standardizzata" per garantire la precisione, con i seguenti passaggi:
1. **Knit the Swatch**:
   - Utilizzare il filato e gli aghi effettivi per il progetto per lavorare a maglia un campione di almeno 15 cm×15 cm (per evitare la deformazione del bordo che influisca sulla misurazione);
   - Il motivo del punto deve corrispondere al prodotto finito (la densità varia in modo significativo tra i diversi punti come il punto stockinette e il punto brioche).
2. **Blocco del vapore (passo critico)**:
   - Ferro da stiro a vapore il campione in base al materiale del filato (lana/cotone/fibra sintetica) (solo vapore, senza pressare o allungare);
   - Misurare dopo l'asciugatura naturale (i campioni non bloccati possono ridursi, portando a errori di calcolo del calibro).
3. **Misurazione precisa**:
   - Orizzontale: misurare 10 cm nell'area centrale del campione (evitando 2-3 cm dai bordi) e contare il numero di punti (sono consentiti punti frazionari, ad esempio 18,5 punti);
   - Verticale: misurare 10 cm nella stessa area centrale e contare il numero di righe;
   - Ripeti la misurazione 2-3 volte e prendi la media (per migliorare la precisione).
4. **Calcola i risultati**:
   Esempio: 18 punti orizzontalmente e 24 righe verticalmente entro 10 cm → Il calibro è "18 punti × 24 righe / 10 cm".

### IV. Lavoro a maglia vs. Uncinetto
Le categorie di punti secondari sono uniformemente identificate da "Corto/Medio/Lungo".

| Grado di punto universale | Correlazione del lavoro a maglia | Correlazione all'uncinetto | Caratteristica di densità del nucleo | Fattore di correzione |
|:-----------------------|:----------------------------|:--------------------------|:----------------------|:---------------------------------|
| Corto | Punto calza | Uncinetto singolo (SC) | Più compatto (baseline) | 1.0 |
| Medio | Punto calza inverso | Mezzo doppio uncinetto (HDC) | Moderatamente sciolto | 0,85 |
| Lungo | Punto brioche | Doppio uncinetto (DC) | Estremamente sciolto | 0,7 |
