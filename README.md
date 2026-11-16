# File Cataloger — High-Speed Local Document Indexing Engine

🇬🇧 / 🇺🇸 **ENGLISH** | [🇮🇹 Vai alla versione in Italiano](#-italiano)

[![Portfolio](https://img.shields.io/badge/Portfolio-antoniangeloflore.com-0d6efd?style=flat-square)](https://antoniangeloflore.com)
[![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20Python%203.12%2B%20%7C%20SQLite-198754?style=flat-square)](https://github.com/pratico)
[![Privacy](https://img.shields.io/badge/Privacy-100%25%20Local%20%2F%20Zero--Cloud-dc3545?style=flat-square)](https://antoniangeloflore.com)

## Product Overview

**File Cataloger** is a private, local-first application for Linux systems, accessible directly from the browser, engineered to index, catalog, and search the entire contents of any folder hierarchy in seconds.

It is built for **SMEs, agencies, operations teams, and professionals** who manage large volumes of files spread across multiple paths and root directories daily, and who need an immediate, structured, and searchable view of their digital archive—without relying on external cloud services or exposing sensitive data.

## The Problem Solved

In every real-world organization, manual file management generates hidden operational costs and concrete bottlenecks:

- **Wasted search time:** Minutes (often hours) lost every day searching for documents, assets, or outdated versions across unorganized folders.
- **Manual errors:** Duplications, misplaced files, and inconsistent classifications caused by "memory-based" cataloging.
- **Lack of visibility:** Inability to quickly answer operational questions such as *"How many files of this type do we have?"* or *"Where is the latest version stored?"*.
- **Cloud vendor lock-in & privacy risks:** External cloud indexing tools that expose confidential corporate documents and impose recurring SaaS subscriptions.

**File Cataloger** eliminates these frictions: a single scan transforms the local filesystem into a structured, persistent archive that can be queried and sorted in real time.

## Operator Workflow

The workflow is straightforward and immediate from the operator's perspective:

1. **Application Launch** — Start the lightweight local service on Linux and open the web interface in any browser.
2. **Target Directory Selection** — Specify the folder or root path to scan.
3. **Recursive Automated Scan** — The engine traverses the directory tree, detecting every file and subfolder and recording core metadata (name, type, extension, size, timestamp, full path).
4. **Exclusion Rules** — Configure custom exclusion filters to ignore irrelevant system directories or file extensions, keeping the index clean and focused.
5. **Persistent Local Cataloging** — All indexed records are stored in a structured local SQLite database, remaining instantly available across sessions.
6. **Instant Search & Multi-Criteria Sorting** — Query files in real time by name, extension, or path, and sort results by name, type, extension, size, date, path, or root.
7. **Integrated Visual Preview** — Preview image assets directly inside the web interface without launching external viewers.

The result: a complete, searchable, and visually browsable archive obtained in a few clicks with zero repetitive manual work.

## Main Features & Operational Benefits (ROI)

| Functionality | Operational Advantage |
|---|---|
| **Recursive Folder Scanning** | Complete indexing of entire directory trees in a single automated pass. |
| **Persistent Local Cataloging** | Data remains saved and queryable over time: no repeated scans, no lost metadata. |
| **Search by Name, Extension & Path** | Instant retrieval of any file: cutting search times from minutes to seconds. |
| **Multi-Criteria Sorting** (name, type, extension, size, date, path, root) | Analyze and audit archives according to current operational priorities. |
| **Integrated Image Preview** | Immediate visual verification directly in the browser for faster decision-making. |
| **Exclusion Configuration** | Clean, high-signal catalogs with zero noise. |
| **100% Local Execution** | Zero data leaves the machine: full GDPR/NDA confidentiality and zero recurring fees. |

**Immediate ROI:** For a team losing even 15 minutes per day searching for files, productivity recovery translates into dozens of hours saved annually through a single local deployment and zero monthly subscriptions.

## High-Level Architecture & Stack

- **Linux** — Native execution environment delivering enterprise stability, security, and predictable resource usage.
- **Python 3.12+** — High-performance local filesystem traversal and metadata extraction engine.
- **SQLite** — Embedded, zero-configuration relational database for fast local persistence.
- **Browser Web Interface** — Instant access from any local browser without installing desktop clients.

## Requirements

- **Linux** Operating System
- **Python 3.12+** (recommended)

## Confidentiality Notice & B2B Licensing

🔒 **Proprietary Software Asset (All Rights Reserved):** This repository serves as a functional and architectural showcase within the Professional Portfolio ([https://antoniangeloflore.com](https://antoniangeloflore.com) — *Italian portal & video demos; English B2B delivery*). For operational security and NDA compliance, the source code and internal implementation details are not publicly exposed.

🤝 **Custom Deployment & White-Label Inquiries:** Available for custom B2B integration, white-label agency licensing, and asynchronous technical consultations (no calls required). Reach out via [antoniangeloflore.com](https://antoniangeloflore.com) or [LinkedIn](https://www.linkedin.com/in/antoniangelo-f-30003622/).

---

<a name="-italiano"></a>
## 🇮🇹 ITALIANO

# Catalogatore File — Motore Locale di Indicizzazione Documentale ad Alte Prestazioni

## Panoramica del Prodotto

**Catalogatore File** è un'applicazione locale privata per sistemi Linux, accessibile direttamente dal browser, progettata per indicizzare, catalogare e ricercare in pochi secondi l'intero contenuto di qualsiasi cartella del sistema.

È pensata per **PMI, agenzie, team operativi e professionisti** che gestiscono quotidianamente grandi volumi di file sparsi su più percorsi e root, e che necessitano di una visione immediata, ordinata e ricercabile del proprio archivio digitale — senza dipendere da servizi cloud esterni.

## Il Problema Risolto

In ogni azienda reale, la gestione manuale dei file genera costi nascosti e colli di bottiglia concreti:

- **Tempo perso nella ricerca:** minuti (spesso ore) spesi ogni giorno per cercare documenti, immagini o versioni obsolete tra cartelle non organizzate.
- **Errori manuali:** duplicazioni, file persi, classificazioni incoerenti dovute alla catalogazione "a memoria".
- **Mancanza di visibilità:** impossibile rispondere rapidamente a domande come *"quanti file di questo tipo abbiamo?"* o *"dove si trova l'ultima versione?"*.
- **Dipendenza da strumenti esterni:** soluzioni cloud che espongono dati sensibili e impongono costi ricorrenti.

**Catalogatore File** elimina questi attriti: una sola scansione trasforma il filesystem locale in un archivio strutturato, consultabile e ordinabile in tempo reale.

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
- **Python 3.12+** — Linguaggio maturo e performante per l'elaborazione locale, ideale per automazioni affidabili e di lunga durata.
- **SQLite** — Database locale integrato: persistenza solida, zero configurazione, zero manutenzione.
- **Interfaccia Web (browser)** — Accessibilità immediata da qualsiasi browser, senza installazione di client aggiuntivi.

Questa combinazione garantisce un'applicazione leggera, reattiva e autosufficiente: un asset software che lavora in background per l'azienda, senza richiedere infrastrutture esterne.

## Requisiti

- Sistema operativo **Linux**
- **Python 3.12+** (consigliato)

## Nota di Riservatezza & Collaborazioni B2B

🔒 **Asset Software Proprietario (Tutti i diritti riservati):** Questo repository ha finalità di presentazione funzionale e architetturale per il Portfolio Professionale ([https://antoniangeloflore.com](https://antoniangeloflore.com)). Per ragioni di sicurezza operativa e accordi di riservatezza (NDA), il codice sorgente e le specifiche infrastrutturali non sono esposti pubblicamente.

🤝 **Sviluppo Custom & Licensing White-Label:** Disponibile per integrazioni B2B su misura, licenze White-Label per agenzie e consulenze tecniche asincrone (zero call). Contatti su [antoniangeloflore.com](https://antoniangeloflore.com) o su [LinkedIn](https://www.linkedin.com/in/antoniangelo-f-30003622/).
