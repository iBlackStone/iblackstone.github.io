---
title: Aiuto per le note di lavoro a maglia
lang: it
---

Knitting Notes ti consente di importare e leggere modelli PDF, quindi aggiungere righelli, testo, immagini, spille informative, pennellate e contatori. L'aggiunta di elementi di pagina o disegno non modifica direttamente il PDF originale.

## Navigazione rapida

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

## Crea e apri un progetto

1. Apri Strumenti e seleziona **Note per maglieria**.
2. Scegli il file PDF che vuoi importare.
3. Il file importato viene visualizzato nell'elenco dei progetti Knitting Notes.
4. Tocca il progetto per continuare dalla tua precedente posizione di lettura e dallo stato di modifica.

Gli utenti gratuiti possono creare fino a un progetto Knitting Notes. L'eliminazione di un progetto non può essere annullata, quindi conferma che non ne hai più bisogno prima.

## Layout dell'editor

### Barra degli strumenti superiore

- **Chiudi**: Torna all'elenco dei progetti e salva lo stato di lettura corrente.
- **Annulla**: Annulla l'ultima operazione di pennello o componente supportata.
- **Rifare**: Ripristina l'operazione che è stata appena annullata.
- **Guida per l'utente**: tocca `? ` per aprire questa pagina di aiuto in qualsiasi momento.
- **Altro**: Rinomina, salva o elimina il progetto corrente.

### Mostra o nascondi le barre degli strumenti

Tocca un'area vuota del PDF per nascondere le barre degli strumenti superiore e inferiore e ottenere più spazio di lettura. Usa i piccoli pulsanti ai bordi dello schermo per mostrarli di nuovo.

Nel tema scuro, l'area di lettura del PDF riduce la luminosità delle pagine bianche per impostazione predefinita. Le barre degli strumenti superiore e inferiore rimangono nere e i colori originali del PDF non sono invertiti. Per visualizzare la luminosità originale, disattivare **Riduci luminosità PDF** dal menu Altro in alto a destra.

### Gesti di lettura di base

- Scorri con un dito per sfogliare il PDF.
- Pizzica con due dita per ingrandire.
- Tocca un componente di pagina per selezionarlo e mostrare i suoi controlli fluttuanti.
- Scorrendo o ingrandendo il PDF si cancella la selezione del componente corrente.

## Barra degli strumenti inferiore

| Strumento | Scopo |
|---|---|
| Pagine | Mostra le miniature delle pagine e le etichette delle pagine per una navigazione rapida |
| Componenti | Scegli un'immagine, un pin informativo, un link al grafico, un testo o un righello |
| Sposta | Torna alla lettura dei PDF, allo scorrimento e allo zoom |
| Pennello | Seleziona un pennello e disegna sulla pagina PDF corrente |
| Gomma | Cancella pennellate |
| Contatore | Mostra o nascondi i contatori del progetto |
| Timer | Monitora manualmente il tempo trascorso in questa sessione |
| Altro | Elementi aperti, colore predefinito, Brush Manager e Ruler Manager |

## Pagine ed etichette

Tocca **Pagine** per aprire il pannello delle miniature:

- Tocca una miniatura per passare a quella pagina.
- Usa l'elenco delle etichette in alto per passare direttamente alle pagine etichettate.
- Un'etichetta di pagina appare nella parte inferiore della sua miniatura.
- Tocca `...` sulla miniatura selezionata per aggiungere, modificare o eliminare un'etichetta.
- Ogni pagina può avere un'etichetta.

Gli utenti gratuiti possono creare fino a due etichette di pagina. Le etichette esistenti possono ancora essere modificate o eliminate.

## Aggiungi componenti della pagina

1. Tocca **Componenti**.
2. Scegli un componente.
3. Il pulsante del componente cambia per mostrare l'elemento selezionato.
4. Tocca la posizione di destinazione sul PDF. Il componente è posizionato con il punto di contatto al centro.
5. L'editor torna automaticamente alla modalità Sposta.

L'aggiunta di nuovi componenti di pagina richiede l'iscrizione. I componenti esistenti rimangono disponibili per la visualizzazione e la modifica.

### Componenti disponibili

#### Regolatori

Usa i righelli per seguire la riga o la colonna corrente. Sono forniti preset di righello orizzontale, verticale e a 45 gradi. I preset possono essere regolati in Ruler Manager.

#### Testo

I componenti di testo supportano più righe. L'ingrandimento della casella di testo rivela più contenuto. Le impostazioni del testo includono il colore del testo, la dimensione del carattere, l'allineamento, la copia e l'incolla.

#### Immagini

Le immagini possono essere selezionate dalla fotocamera, File o Foto. Sono inseriti utilizzando il loro rapporto di aspetto originale e supportano il ridimensionamento e la rotazione proporzionali, ma non lo stretching indipendente del bordo.

#### Pin informativo

Un pin informativo appare come un'icona `i` di dimensioni fisse. Toccalo per leggere la nota. Tocca due volte l'area di testo nel popup per modificare il contenuto.

#### Collegamento al grafico

Un link al grafico collega il PDF a un grafico a maglia esistente nell'app. Una volta collegato, può mostrare una miniatura e aprire direttamente la tabella di lavoro a maglia correlata.

<a id="chart-grid-segmentation"></a>
#### Calibrazione della griglia del grafico

La calibrazione della griglia del grafico trasforma un grafico a pixel o un grafico a maglia già stampato in un PDF in una fonte di griglia riutilizzabile con informazioni su righe e colonne.

1. Scegli **Griglia del grafico** da Componenti, quindi tocca l'area del grafico per posizionare la cornice.
2. Trascina l'area vuota all'interno della cornice per posizionarla. Usa le maniglie esterne per ridimensionarlo o ruotarlo.
3. La guida orizzontale inizia in alto e la guida verticale inizia a sinistra. Sposta ogni guida e regola il suo spessore fino a quando entrambi i bordi della guida corrispondono a due linee della griglia vicine.
4. Tocca **Allinea** per agganciare entrambi gli assi al periodo completo più vicino. Anche le regolazioni quasi esatte scattano automaticamente e forniscono un feedback tattile.
5. Rosso significa che la griglia ha ancora bisogno di attenzione. Un fotogramma e una griglia confermati diventano verdi e mostrano **Allineato**. Spostare, ridimensionare o ruotare il telaio richiede un nuovo allineamento.
6. **Lock Frame** protegge solo il telaio esterno mantenendo entrambe le guide modificabili. L'azione successiva **Lock** blocca l'intero componente.
7. **Anteprima immagine griglia** controlla il risultato estratto senza creare un progetto di lavoro a maglia.
8. **Crea Counter Chart** crea e lega un grafico a maglia. Successivamente la stessa voce apre o sincronizza quel grafico invece di creare una nuova copia ogni volta.
9. **More** passa tra le guide di calibrazione e la griglia completa e cambia la direzione di lettura della riga o della colonna. Un componente non selezionato mantiene un piccolo indicatore di griglia; tocca due volte uno collegato per aprire il suo grafico.

Dopo aver aperto l'editor di maglieria, passa da **Pixel** a **Symbol Drawing**. Il disegno dei pixel campiona i colori delle celle calibrate e consente di regolare, unire, dividere o ignorare i gruppi di colori in **Conferma piano di disegno**. Il disegno dei simboli raggruppa ogni immagine della cella e apre **Conferma simboli**, dove è possibile confrontare il ritaglio di origine, il punto e lo sfondo della cella. Il testo della legenda PDF e i simboli precedentemente confermati vengono utilizzati come indizi di riconoscimento e le correzioni dell'utente vengono ricordate. Entrambi i percorsi creano prima un'anteprima temporanea; tocca **Applica a Canvas** solo dopo averla controllata. Verifica tutti i bordi, il conteggio delle righe e delle colonne e le indicazioni di lettura prima dell'uso.

## Modifica componenti della pagina

Tocca un componente per mostrare la sua cornice di selezione tratteggiata, le maniglie e i controlli fluttuanti. Le azioni disponibili dipendono dal tipo di componente:

- Trascina all'interno del componente per spostarlo.
- Trascina una maniglia di bordo per cambiare larghezza o altezza.
- Trascina la maniglia in alto a destra per scalare proporzionalmente.
- Trascina la maniglia superiore per ruotare.
- Usa Colore per cambiare il colore del componente.
- Usa l'opacità per regolare la trasparenza dello sfondo.
- Usa Transform per angolazioni rapide e impostazioni di scala.
- Usa Elimina per rimuovere il componente.

Non tutti i componenti supportano ogni azione. Ad esempio, le immagini non possono allungare i singoli bordi, mentre i pin informativi e i collegamenti grafici non possono ruotare o ridimensionare.

### Blocca e sblocca

- Quando è bloccata, la barra degli strumenti mobile collassa in un singolo pulsante **Sblocca**.
- Un righello bloccato può ancora essere spostato, ma non può essere ridimensionato, ridimensionato, ruotato o ridimensionato.
- **Lock Frame** su una griglia del grafico impedisce solo modifiche accidentali del telaio esterno; le guide interne rimangono modificabili. Usa la normale azione **Lock** per congelare l'intero componente.
- Il testo bloccato, le immagini, i pin informativi, i collegamenti al grafico e altri componenti non possono essere spostati o modificati.
- Tocca **Sblocca** per ripristinare tutti i controlli e le maniglie.

## Pennelli e gomme

Seleziona un pennello da **Pennello** e disegna nella pagina corrente.

- Un preset pennello contiene la sua forma, dimensione, colore e opacità.
- Brush Manager ti consente di aggiungere, modificare, eliminare e riordinare i preset.
- I preset vicino alla parte superiore dell'elenco vengono visualizzati per primi nell'editor.
- La gomma rimuove solo pennellate. Non elimina righelli, testo, immagini o altri componenti.
- Elimina i componenti utilizzando il pulsante o gli elementi di elimina fluttuante.

L'aggiunta di nuovi preset di pennello richiede l'iscrizione. I pennelli predefiniti ed esistenti rimangono utilizzabili.

## Tempo trascorso

Il timer inferiore è separato dai contatori di riga. Dopo averlo avviato manualmente, il salvataggio del foglio lo mantiene in esecuzione; lasciando le note del progetto o l'invio dell'app in background si ferma e lo salva. Le note aperte da un progetto assegnano la sessione a quel progetto, mentre le note autonome mantengono una cronologia di sole note.

## Contatori

Ogni progetto Knitting Notes contiene almeno un contatore.

- Tocca il numero per aggiungere 1.
- Tocca `-` per sottrarre 1.
- Tocca Ripristina per riportare il valore a 0.
- Tocca `...` o premi a lungo un contatore per aprirne il menu.
- Il menu supporta la modifica, l'immissione diretta del numero, il colore, la ridenominazione e l'eliminazione.
- Le righe definiscono il valore massimo. Dopo che il massimo è stato superato, contando si riavvia da 0.
- Il primo contatore in un progetto non può essere eliminato.

Ogni pagina orizzontale del contatore mostra fino a tre contatori. Scorri orizzontalmente quando ce ne sono più di tre; un indicatore di pagina appare in alto. Usa il pulsante in alto a destra per passare dall'altezza piena a quella compatta.

Gli utenti gratuiti possono utilizzare fino a tre contatori.

## Elementi

Apri **Altro > Elementi** per gestire i componenti e le note di pennello in un unico posto.

- L'anteprima a sinistra aiuta a identificare l'elemento e il suo contorno.
- Tocca un elemento per individuarlo nella sua pagina PDF.
- Blocca o sblocca i componenti.
- Elimina gli elementi che non sono più necessari.
- Le pennellate vicine sono raggruppate in un'anteprima delle note più riconoscibile.

## Preimpostazioni predefinite di colore, pennelli e righello

Il menu **Altro** in basso contiene impostazioni condivise:

- **Colore predefinito** influisce sui componenti aggiunti in seguito.
- **Brush Manager** gestisce i preset di pennello condivisi da tutti i progetti Knitting Notes.
- **Ruler Manager** gestisce i preset del righello condivisi da tutti i progetti Knitting Notes.

La modifica di un preset condiviso non altera automaticamente componenti o tratti che sono già stati aggiunti.

## Salva, Annulla e Ripristina

- Posizione di lettura, etichette di pagina, contatori e la maggior parte delle modifiche vengono memorizzate con il progetto.
- Per salvare immediatamente, usa **Top Altro > Salva**.
- Annulla e rido si applicano alle operazioni di componente e pennello supportate nella sessione di modifica corrente.
- La cronologia di annullaggio potrebbe non rimanere dopo aver lasciato e riaperto un progetto, ma il contenuto della pagina salvata viene ripristinato.

## iCloud e più dispositivi

I backup di Knitting Notes includono il database del progetto, i file PDF e le risorse di immagini relative ai PDF. Il progetto completo viene visualizzato su un altro dispositivo solo dopo che la sincronizzazione o il ripristino di iCloud dell'app è terminato.

Si prega di notare:

- Il backup di iCloud non è una collaborazione in tempo reale.
- I PDF di grandi dimensioni potrebbero richiedere più tempo per il caricamento e il ripristino.
- Non eliminare il progetto o il PDF dal dispositivo originale prima del completamento del ripristino.
- I backup più vecchi solo per database potrebbero non contenere il PDF originale.

## Domande frequenti

### Perché non posso scorrere il PDF dopo aver selezionato un componente?

I gesti del componente hanno la priorità all'interno dell'area di colpi del componente. Tocca un'area vuota, passa alla modalità Sposta o inizia a ingrandire il PDF per cancellare la selezione.

### Perché la gomma non può eliminare un righello o un testo?

La gomma gestisce solo pennellate. Usa il pulsante Elimina del componente o gli elementi per altri elementi.

### Perché un righello bloccato può ancora muoversi?

I righelli devono essere riposizionati seguendo uno schema. Il blocco conserva le loro dimensioni, angolazione e stile, mentre altri componenti bloccati rimangono completamente fissi.

### Perché tocco la pagina dopo aver scelto un componente?

Il flusso di lavoro choose-then-place aggiunge il componente esattamente dove è necessario ed evita di spostarlo dal centro della pagina in seguito.

### Perché alcune funzionalità mostrano un prompt di iscrizione?

La versione gratuita supporta l'importazione di base, la lettura e l'uso limitato. Le azioni avanzate come l'aggiunta di componenti della pagina o la creazione di più preset di pennello richiedono l'iscrizione.
