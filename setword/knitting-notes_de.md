---
Titel: Stricknotizen Hilfe
lang: de
---

Mit Knitting Notes können Sie PDF-Muster importieren und lesen und dann Lineale, Text, Bilder, Informationsnadeln, Pinselstriche und Zähler hinzufügen. Das Hinzufügen von Seitenelementen oder Zeichnungen ändert das Original-PDF nicht direkt.

## Schnelle Navigation

- [Create and Open a Project](#create-and-open-a-project)
- [Editor Layout](#editor-layout)
- [Bottom Toolbar](#bottom-toolbar)
- [Pages and Labels](#pages-and-labels)
- [Add Page Components](#add-page-components)
- [Chart Grid Calibration](#chart-grid-segmentation)
- [Edit and Lock Components](#edit-page-components)
- [Brushes and Eraser](#brushes-and-eraser)
- [Counters](#counters)
- [Time spent](#time-spent)
- [Elements](#elements)
- [Save and Multiple Devices](#save-undo-and-restore)
- [Frequently Asked Questions](#frequently-asked-questions)

## Erstellen und öffnen Sie ein Projekt

1. Öffnen Sie Werkzeuge und wählen Sie **Strickennotizen**.
2. Wählen Sie die PDF-Datei aus, die Sie importieren möchten.
3. Die importierte Datei wird in der Projektliste "Stricknotizen" angezeigt.
4. Tippen Sie auf das Projekt, um mit Ihrer vorherigen Leseposition und Ihrem Bearbeitungsstatus fortzufahren.

Kostenlose Benutzer können bis zu einem Knitting Notes-Projekt erstellen. Das Löschen eines Projekts kann nicht rückgängig gemacht werden, also bestätigen Sie zuerst, dass Sie es nicht mehr benötigen.

## Editor-Layout

### Obere Symbolleiste

- **Schließen**: Kehren Sie zur Projektliste zurück und speichern Sie den aktuellen Lesestatus.
- **Undo**: Den zuletzt unterstützten Pinsel- oder Komponentenvorgang rückgängig machen.
- **Wiederholt**: Stellen Sie den Vorgang wieder her, der gerade rückgängig gemacht wurde.
- **Benutzerhandbuch**: Tippen Sie auf `? ` um diese Hilfeseite jederzeit zu öffnen.
- **Mehr**: Das aktuelle Projekt umbenennen, speichern oder löschen.

### Symbolleisten ein- oder ausblenden

Tippen Sie auf einen leeren Bereich der PDF-Datei, um die obere und untere Symbolleiste auszublenden und mehr Leseplatz zu gewinnen. Verwenden Sie die kleinen Tasten an den Bildschirmrändern, um sie erneut anzuzeigen.

Im dunklen Thema reduziert der PDF-Lesebereich standardmäßig die Helligkeit weißer Seiten. Die obere und untere Symbolleiste bleiben schwarz, und die Originalfarben des PDF sind nicht umgekehrt. Um die ursprüngliche Helligkeit anzuzeigen, deaktiiert **PDF-Helligkeit reduzieren** im Menü Mehr oben rechts.

### Grundlegende Lesegesten

- Wischen Sie mit einem Finger, um das PDF zu durchsuchen.
- Drücken Sie mit zwei Fingern, um zu zoomen.
- Tippen Sie auf eine Seitenkomponente, um sie auszuwählen und ihre schwebenden Steuerelemente anzuzeigen.
- Durch Scrollen oder Vergrößern des PDF-Dokuments wird die aktuelle Komponentenauswahl gelöscht.

## Untere Symbolleiste

| Werkzeug | Zweck |
|---|---|
| Seiten | Seiten-Thumbnails und Seitenbeschriftungen für eine schnelle Navigation anzeigen |
| Komponenten | Wählen Sie ein Bild, eine Informationsnadel, einen Diagrammlink, einen Text oder ein Lineal |
| Verschieben | Zurück zum PDF-Lesen, Scrollen und Zoomen |
| Pinsel | Wählen Sie einen Pinsel und zeichnen Sie auf der aktuellen PDF-Seite |
| Radiergummi | Pinselstriche löschen |
| Zähler | Projektzähler ein- oder ausblenden |
| Timer | Zeit, die in dieser Sitzung verbracht wird, manuell verfolgen |
| Mehr | Offene Elemente, Standardfarbe, Pinsel-Manager und Lineal-Manager |

## Seiten und Beschriftungen

Tippen Sie auf **Seiten**, um das Miniaturansichtsfeld zu öffnen:

- Tippen Sie auf eine Miniaturansicht, um zu dieser Seite zu springen.
- Verwenden Sie die Beschriftungsliste oben, um direkt zu den beschrifteten Seiten zu springen.
- Am unteren Rand der Miniaturansicht erscheint ein Seitenbeschriftung.
- Tippen Sie auf `...` auf der ausgewählten Miniaturansicht, um ein Label hinzuzufügen, zu bearbeiten oder zu löschen.
- Jede Seite kann ein Etikett haben.

Kostenlose Benutzer können bis zu zwei Seitenbeschriftungen erstellen. Vorhandene Etiketten können weiterhin bearbeitet oder gelöscht werden.

## Seitenkomponenten hinzufügen

1. Tippen Sie auf **Komponenten**.
2. Wählen Sie eine Komponente aus.
3. Die Komponentenschaltfläche ändert sich, um das ausgewählte Element anzuzeigen.
4. Tippen Sie auf die Zielposition im PDF. Die Komponente wird mit dem Berührungspunkt in der Mitte platziert.
5. Der Editor kehrt automatisch in den Move-Modus zurück.

Das Hinzufügen neuer Seitenkomponenten erfordert eine Mitgliedschaft. Vorhandene Komponenten können weiterhin angezeigt und bearbeitet werden.

### Verfügbare Komponenten

#### Herrscher

Verwenden Sie Lineale, um der aktuellen Zeile oder Spalte zu folgen. Horizontale, vertikale und 45-Grad-Linealvoreinstellungen werden bereitgestellt. Voreinstellungen können im Ruler Manager angepasst werden.

#### Text

Textkomponenten unterstützen mehrere Zeilen. Durch die Vergrößerung des Textfelds wird mehr Inhalt angezeigt. Zu den Texteinstellungen gehören Textfarbe, Schriftgröße, Ausrichtung, Kopieren und Einfügen.

#### Bilder

Bilder können aus der Kamera, Dateien oder Fotos ausgewählt werden. Sie werden mit ihrem ursprünglichen Seitenverhältnis eingesetzt und unterstützen eine proportionale Skalierung und Drehung, aber keine unabhängige Kantendehnung.

#### Informationsstift

Ein Informations-Pin wird als `i`-Symbol mit fester Größe angezeigt. Tippen Sie darauf, um die Notiz zu lesen. Doppeltippen Sie auf den Textbereich im Popup, um den Inhalt zu bearbeiten.

#### Diagramm-Link

Ein Diagramm-Link verbindet das PDF mit einer vorhandenen Stricktabelle in der App. Einmal verlinkt, kann es eine Miniaturansicht anzeigen und das zugehörige Strickdiagramm direkt öffnen.

<a id="chart-grid-segmentation"></a>
#### Diagramm-Rasterkalibrierung

Die Chart Grid Calibration verwandelt ein Pixeldiagramm oder ein Strickdiagramm, das bereits in einem PDF gedruckt ist, in eine wiederverwendbare Rasterquelle mit Zeilen- und Spalteninformationen.

1. Wählen Sie **Diagrammraster** aus Komponenten und tippen Sie dann auf den Diagrammbereich, um den Rahmen zu platzieren.
2. Ziehen Sie den leeren Bereich innerhalb des Rahmens, um ihn zu positionieren. Verwenden Sie die äußeren Griffe, um die Größe zu ändern oder zu drehen.
3. Die horizontale Führung beginnt oben und die vertikale Führung beginnt links. Bewegen Sie jede Führung und passen Sie ihre Dicke an, bis beide Führungskanten mit zwei benachbarten Gitterlinien übereinstimmen.
4. Tippen Sie auf **Ausrichten**, um beide Achsen auf ihre nächste vollständige Periode zu klicken. Nahezu genaue Anpassungen schnappen auch automatisch und liefern haptisches Feedback.
5. Rot bedeutet, dass das Gitter noch Aufmerksamkeit braucht. Ein bestätigter Rahmen und ein Raster werden grün und zeigen **Ausgerichtet** an. Das Verschieben, die Größenänderung oder das Drehen des Rahmens erfordert eine erneute Ausrichtung.
6. **Lock Frame** schützt nur den äußeren Rahmen, während beide Hilfslinien bearbeitbar bleiben. Die spätere **Lock**-Aktion sperrt die gesamte Komponente.
7. **Vorschau-Rasterbild** überprüft das extrahierte Ergebnis, ohne ein Strickprojekt zu erstellen.
8. **Create Counter Chart** erstellt und bindet ein Strickdiagramm. Später öffnet oder synchronisiert derselbe Eintrag dieses Diagramm, anstatt jedes Mal eine neue Kopie zu erstellen.
9. **Mehr** wechselt zwischen Kalibrierungsführungen und dem vollen Raster und ändert die Leserichtung der Zeilen oder Spalte. Eine nicht ausgewählte Komponente behält eine kleine Rastermarkierung bei; tippen Sie doppelt auf eine verknüpfte, um ihr Diagramm zu öffnen.

Wechseln Sie nach dem Öffnen des Strickeditors zwischen **Pixel** und **Symbolzeichnung**. Die Pixelzeichnung samplet die kalibrierten Zellfarben und ermöglicht es Ihnen, Farbgruppen in **Zeichnungsplan bestätigen** anzupassen, zusammenzuführen, zu teilen oder zu ignorieren. Symbolzeichnung gruppiert jedes Zellenbild und öffnet **Symbole bestätigen**, wo Sie den Quellschnitt, den Stich und den Zellhintergrund vergleichen können. PDF-Legendentext und zuvor bestätigte Symbole werden als Erkennungshinweise verwendet, und Benutzerkorrekturen werden gespeichert. Beide Pfade erstellen zuerst eine temporäre Vorschau; tippen Sie erst nach der Überprüfung auf **Auf Canvas anbringen**. Überprüfen Sie vor der Verwendung alle Kanten, die Zeilen- und Spaltenzahlen und das Lesen der Anweisungen.

## Seitenkomponenten bearbeiten

Tippen Sie auf eine Komponente, um den gepunkteten Auswahlrahmen, die Griffe und die schwebenden Steuerelemente anzuzeigen. Verfügbare Aktionen hängen vom Komponententyp ab:

- Ziehen Sie in die Komponente, um sie zu verschieben.
- Ziehen Sie einen Kantengriff, um die Breite oder Höhe zu ändern.
- Ziehen Sie den oberen rechten Griff, um proportional zu skalieren.
- Ziehen Sie den oberen Griff, um sich zu drehen.
- Verwenden Sie "Farbe", um die Farbe der Komponente zu ändern.
- Verwenden Sie die Deckkraft, um die Hintergrundtransparenz anzupassen.
- Verwenden Sie "Transformieren" für schnelle Winkel und Skalierungseinstellungen.
- Verwenden Sie "Löschen", um die Komponente zu entfernen.

Nicht jede Komponente unterstützt jede Aktion. Beispielsweise können Bilder einzelne Kanten nicht ausdehnen, während Informations- und Diagrammlinks nicht gedreht oder skaliert werden können.

### Sperren und Entsperren

- Wenn sie gesperrt ist, wird die schwebende Symbolleiste zu einer einzigen **Entsperren**-Taste zusammengefasst.
- Ein verriegeltes Lineal kann immer noch verschoben werden, aber es kann nicht in der Größe geändert, skaliert, gedreht oder neu gestaltet werden.
- **Lock Frame** auf einem Diagrammraster verhindert nur versehentliche Änderungen des äußeren Rahmens; die internen Führungen bleiben bearbeitbar. Verwenden Sie die normale **Lock**-Aktion, um die gesamte Komponente einzufrieren.
- Gesperrter Text, Bilder, Informations-Pins, Diagramm-Links und andere Komponenten können nicht verschoben oder bearbeitet werden.
- Tippen Sie auf **Entsperren**, um die vollständigen Steuerelemente und Griffe wiederherzustellen.

## Pinsel und Radiergummi

Wählen Sie einen Pinsel aus **Pinsel** und zeichnen Sie auf der aktuellen Seite.

- Eine Pinselvoreinstellung enthält ihre Form, Größe, Farbe und Deckkraft.
- Mit dem Pinsel-Manager können Sie Voreinstellungen hinzufügen, bearbeiten, löschen und neu anordnen.
- Voreinstellungen am Anfang der Liste werden zuerst im Editor angezeigt.
- Der Radiergummi entfernt nur Pinselstriche. Es werden keine Lineale, Texte, Bilder oder andere Komponenten gelöscht.
- Löschen Sie Komponenten mit ihrer schwebenden Schaltfläche "Löschen" oder "Elemente".

Das Hinzufügen neuer Pinselvoreinstellungen erfordert eine Mitgliedschaft. Standard- und vorhandene Pinsel bleiben verwendbar.

## Zeit verbracht

Der untere Timer ist getrennt von den Zeilenzählern. Nachdem Sie es manuell gestartet haben, hält das Verwerfen des Blattes es am Laufen; das Verlassen von Projektnotizen oder das Senden der App in den Hintergrund stoppt und speichert es. Notizen, die von einem Projekt geöffnet wurden, weisen diesem Projekt die Sitzung zu, während eigenständige Notizen einen Verlauf nur mit Notizen beibehalten.

## Zähler

Jedes Knitting Notes-Projekt enthält mindestens einen Zähler.

- Tippen Sie auf die Zahl, um 1 hinzuzufügen.
- Tippen Sie auf `-`, um 1 zu subtrahieren.
- Tippen Sie auf Zurücksetzen, um den Wert auf 0 zurückzugeben.
- Tippen Sie auf `...` oder drücken Sie lange auf einen Zähler, um sein Menü zu öffnen.
- Das Menü unterstützt die Bearbeitung, direkte Eingabe von Zahlen, Farbe, Umbenennen und Löschen.
- Zeilen definiert den Maximalwert. Nachdem das Maximum überschritten wurde, startet das Zählen von 0 neu.
- Der erste Zähler in einem Projekt kann nicht gelöscht werden.

Jede horizontale Zählerseite zeigt bis zu drei Zähler an. Wischen Sie horizontal, wenn es mehr als drei sind; oben erscheint eine Seitenanzeige. Verwenden Sie die obere rechte Taste, um zwischen voller und kompakter Höhe zu wechseln.

Kostenlose Benutzer können bis zu drei Zähler verwenden.

## Element

Öffnen Sie **Mehr > Elemente**, um Komponenten und Notizen an einem Ort zu verwalten.

- Die Vorschau auf der linken Seite hilft, das Element und seinen Umriss zu identifizieren.
- Tippen Sie auf ein Element, um es auf seiner PDF-Seite zu finden.
- Komponenten sperren oder entsperren.
- Löschen Sie Elemente, die nicht mehr benötigt werden.
- In der Nähe werden Pinselstriche in einer besser erkennbaren Notizvorschau zusammengefasst.

## Standardfarbe, Pinsel und Linealvoreinstellungen

Das untere Menü **Mehr** enthält freigegebene Einstellungen:

- **Standardfarbe** wirkt sich auf Komponenten aus, die später hinzugefügt werden.
- **Brush Manager** verwaltet Pinselvoreinstellungen, die von allen Knitting Notes-Projekten geteilt werden.
- **Ruler Manager** verwaltet Lineal-Voreinstellungen, die von allen Knitting Notes-Projekten gemeinsam genutzt werden.

Das Ändern einer freigegebenen Voreinstellung ändert nicht automatisch Komponenten oder Striche, die bereits hinzugefügt wurden.

## Speichern, Rückgängig und Wiederherstellen

- Leseposition, Seitenbeschriftungen, Zähler und die meisten Bearbeitungen werden mit dem Projekt gespeichert.
- Um sofort zu speichern, verwenden Sie **Top Mehr > Speichern**.
- Rückgängig und Rückgängig machen gilt für unterstützte Komponenten- und Pinselvorgänge in der aktuellen Bearbeitungssitzung.
- Der Rückgängig-Verlauf bleibt möglicherweise nicht bestehen, nachdem Sie ein Projekt verlassen und wieder öffnen, aber der Inhalt der gespeicherten Seite wird wiederhergestellt.

## iCloud und mehrere Geräte

Knitting Notes-Backups enthalten die Projektdatenbank, PDF-Dateien und PDF-bezogene Bildressourcen. Das vollständige Projekt wird erst auf einem anderen Gerät angezeigt, nachdem die iCloud-Synchronisierung oder Wiederherstellung der App abgeschlossen ist.

Bitte beachten Sie:

- iCloud-Backup ist keine Echtzeit-Zusammenarbeit.
- Das Hochladen und Wiederherstellen großer PDFs kann länger dauern.
- Löschen Sie das Projekt oder das PDF nicht vom ursprünglichen Gerät, bevor die Wiederherstellung abgeschlossen ist.
- Ältere reine Datenbank-Backups enthalten möglicherweise nicht das Original-PDF.

## Häufig gestellte Fragen

### Warum kann ich nicht durch das PDF scrollen, nachdem ich eine Komponente ausgewählt habe?

Komponentengesten haben Vorrang innerhalb des Trefferbereichs der Komponente. Tippen Sie auf einen leeren Bereich, wechseln Sie in den Verschieben-Modus oder zoomen Sie die PDF-Datei, um die Auswahl zu löschen.

### Warum kann der Radiergummi ein Lineal oder einen Text nicht löschen?

Der Radiergummi verarbeitet nur Pinselstriche. Verwenden Sie die Schaltfläche "Löschen" oder "Elemente" der Komponente für andere Elemente.

### Warum kann sich ein verriegeltes Lineal noch bewegen?

Die Lineale müssen neu positioniert werden, während sie einem Muster folgen. Beim Verriegeln bleiben Größe, Winkel und Stil erhalten, während andere gesperrte Komponenten vollständig fixiert bleiben.

### Warum tippe ich auf die Seite, nachdem ich eine Komponente ausgewählt habe?

Der Workflow "Auswählen" fügt die Komponente genau dort hinzu, wo sie benötigt wird, und vermeidet es, sie später aus dem Seitenzentrum zu verschieben.

### Warum zeigen einige Funktionen eine Mitgliedschaftsaufforderung an?

Die kostenlose Version unterstützt den einfachen Import, das Lesen und die eingeschränkte Nutzung. Erweiterte Aktionen wie das Hinzufügen von Seitenkomponenten oder das Erstellen von weiteren Pinselvoreinstellungen erfordern eine Mitgliedschaft.

