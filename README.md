# Catalogatore File

## Panoramica del Prodotto

**Catalogatore File** è un'applicazione locale privata per sistemi Linux, accessibile direttamente dal browser, progettata per indicizzare, catalogare e ricercare in pochi secondi l'intero contenuto di qualsiasi cartella del sistema.

È pensata per **PMI, agenzie, team operativi e professionisti** che gestiscono quotidianamente grandi volumi di file sparsi su più percorsi e root, e che necessitano di una visione immediata, ordinata e ricercabile del proprio archivio digitale — senza dipendere da servizi cloud esterni.

## Il Problema Risolto

In ogni azienda reale, la gestione manuale dei file genera costi nascosti e colli di bottiglia concreti:

- **Tempo perso nella ricerca:** minuti (spesso ore) spesi ogni giorno per cercare documenti, immagini o versioni obsolete tra cartelle non organizzate.
- **Errori manuali:** duplicazioni, file persi, classificazioni incoerenti dovute alla catalogazione "a memoria".
- **Mancanza di visibilità:** impossibile rispondere rapidamente a domande come *"quanti file di questo tipo abbiamo?"* o *"dove si trova l'ultima versione?"*.
- **Dipendenza da strumenti esterni:** soluzioni cloud che espongono dati sensibili e impongono costi ricorrenti.

Catalogatore File elimina questi attriti: una sola scansione trasforma il filesystem locale in un archivio strutturato, consultabile e ordinabile in tempo reale.

## Come Funziona (Flusso Operativo Utente)

L'utilizzo è semplice e immediato, dal punto di vista dell'operatore:

1. **Avvio dell'applicazione** — L'utente avvia il servizio sul proprio computer Linux e accede all'interfaccia dal browser.
2. **Scelta della cartella da scansionare** — L'utente indica la cartella (o il percorso root) da analizzare.
3. **Scansione automatica** — Il sistema attraversa ricorsivamente la cartella, rilevando ogni file e sottocartella, e ne registra le informazioni principali (nome, tipo, estensione, dimensione, data, percorso).
4. **Applicazione delle esclusioni** — L'utente può configurare regole di esclusione per ignorare cartelle o tipi di file non rilevanti, mantenendo il catalogo pulito e mirato.
5. **Catalogazione persistente** — Tutti i risultati vengono salvati in un catalogo locale strutturato, che resta disponibile anche tra sessioni successive.
6. **Ricerca e consultazione** — L'utente cerca istantaneamente per nome, estensione o percorso, e ordina i risultati per nome, tipo, estensione, dimensione, data, percorso o root.
7. **Anteprima visiva** — Per i file immagine, è possibile visualizzare un'anteprima diretta dall'interfaccia, senza aprire gestori esterni.

Il risultato finale: un archivio completo, ricercabile e visivamente consultabile, ottenuto con pochi clic e zero intervento manuale ripetitivo.

## Funzionalità Principali & Vantaggi Operativi (ROI)

| Funzionalità | Vantaggio Operativo |
|---|---|
| **Scansione ricorsiva di cartelle** | Indicizzazione completa di interi archivi in un'unica operazione, senza lavoro manuale. |
| **Catalogazione persistente** | I dati restano salvati e consultabili nel tempo: nessuna scansione ripetuta, nessuna perdita di informazioni. |
| **Ricerca per nome, estensione e percorso** | Ritrovamento immediato di qualsiasi file: da minuti di ricerca manuale a secondi. |
| **Ordinamento multi-criterio** (nome, tipo, estensione, dimensione, data, percorso, root) | Analisi e organizzazione dell'archivio secondo le priorità operative del momento. |
| **Anteprima immagini integrata** | Verifica visiva immediata senza aprire applicazioni esterne: decisioni più rapide. |
| **Configurazione esclusioni** | Cataloghi puliti e pertinenti: zero rumore, massima rilevanza dei risultati. |
| **Funzionamento 100% locale** | Nessun dato lascia la macchina: riservatezza totale e nessun costo ricorrente. |

**ROI immediato:** per un team che perde anche solo 15 minuti al giorno nella ricerca di file, il recupero di produttività si traduce in decine di ore lavorative risparmiate ogni anno, con un'unica installazione locale e zero abbonamenti.

## Tecnologie Utilizzate (Ad Alto Livello)

- **Linux** — Piattaforma nativa di esecuzione: stabilità, sicurezza e affidabilità operativa di livello enterprise.
- **Python** — Linguaggio maturo e performante per l'elaborazione locale, ideale per automazioni affidabili e di lunga durata.
- **SQLite** — Database locale integrato: persistenza solida, zero configurazione, zero manutenzione.
- **Interfaccia Web (browser)** — Accessibilità immediata da qualsiasi browser, senza installazione di client aggiuntivi.

Questa combinazione garantisce un'applicazione leggera, reattiva e autosufficiente: un asset software che lavora in background per l'azienda, senza richiedere infrastrutture esterne.

## Requisiti

- Sistema operativo **Linux**
- **Python 3.12+** (consigliato)

## Nota di Riservatezza

🔒 **Asset Software Proprietario:** Questo repository ha finalità di presentazione funzionale per il Portfolio Professionale (antoniangeloflore.com). Per ragioni di sicurezza operativa e accordi di riservatezza (NDA), il codice sorgente e le specifiche infrastrutturali non sono esposti pubblicamente.
