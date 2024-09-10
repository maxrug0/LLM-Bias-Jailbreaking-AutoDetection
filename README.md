# Studio dei Bias nei Large Language Models tramite Jailbreaking e Rilevamento Automatico

Benvenuti in questa repository, che contiene il codice e i risultati degli esperimenti condotti nell'ambito della tesi intitolata *"Studio dei bias mediante tecniche di jailbreaking e rilevamento automatico"*. La tesi esplora il problema dei bias presenti nei Large Language Models (LLM) e propone una metodologia innovativa che combina tecniche di *jailbreaking* con un sistema di rilevamento automatico basato su un modello linguistico che funge da giudice.

## Struttura della repository

La repository è organizzata in due principali directory:

### 1. `notebooks/`
Questa cartella contiene i notebook Jupyter utilizzati per condurre gli esperimenti. I notebook seguono un flusso ben definito:

- **Valutazione automatizzata**: Utilizzo di un modello linguistico per valutare automaticamente le risposte degli LLM testati in termini di bias.
- **Valutazione iniziale**: Raccolta e analisi preliminare delle risposte fornite dagli LLM senza manipolazioni avversarie.
- **Analisi avversaria**: Sperimentazione con tecniche di *jailbreaking* per indurre comportamenti bias negli LLM, testando la loro resilienza.
- **Visualizzazioni e analisi finale**: Creazione di grafici e visualizzazioni per rappresentare i risultati, evidenziando la presenza e l'entità dei bias rilevati.

I notebook includono istruzioni dettagliate per guidare l'utente attraverso ogni fase del processo. Non sono necessarie configurazioni avanzate: eventuali accortezze o configurazioni particolari verranno indicate direttamente all'interno dei notebook.

### 2. `results/`
In questa cartella sono presenti i file CSV che contengono i risultati delle varie fasi sperimentali. Ogni file CSV include:

- **Risposte generate dai modelli** durante gli esperimenti.
- **Valutazioni del modello giudice** rispetto alla presenza di bias.
- **Metriche intermedie**: Nei file CSV sono presenti le metriche intermedie utilizzate per il calcolo delle metriche finali di robustezza, fairness e sicurezza. Le metriche intermedie includono tassi di stereotipo, controstereotipo, debiased e di rifiuto. Questi tassi sono combinati per derivare le metriche finali.

## Contenuti principali

Gli esperimenti si concentrano su tre aspetti chiave:

1. **Analisi dei Bias negli LLM**: Valutazione delle risposte degli LLM a diverse categorie di input, per identificare distorsioni dovute a bias di genere, razziali e altro.
2. **Tecniche di Jailbreaking**: Manipolazioni intenzionali degli input per far emergere bias latenti nei modelli.
3. **Rilevamento Automatico dei Bias**: Uso di un modello linguistico come "giudice" per analizzare le risposte dei modelli esaminati e rilevare automaticamente la presenza di bias.

## Come utilizzare questa repository

1. **Esegui gli esperimenti**: Puoi esplorare i notebook Jupyter per capire come sono stati condotti gli esperimenti di rilevamento dei bias. 
2. **Analizza i risultati**: I file CSV presenti nella cartella `results/` contengono i risultati dettagliati di ogni esperimento. Puoi analizzare questi dati per comprendere l'entità dei bias nei modelli testati.
3. **Modifica e personalizza**: Puoi adattare i notebook per testare altri modelli o per esplorare altre forme di bias. Sentiti libero di sperimentare e contribuire con le tue scoperte!

## Obiettivi della Tesi

Questa tesi si propone di:

- Fornire una panoramica completa del problema dei bias nei LLM e delle loro implicazioni etiche e pratiche.
- Introdurre una metodologia innovativa per il rilevamento e la mitigazione dei bias tramite tecniche avanzate di jailbreaking e rilevamento automatico.
- Contribuire allo sviluppo di sistemi LLM più equi, affidabili e sicuri, proponendo soluzioni concrete per l'identificazione e la riduzione dei bias.

## Autore

Questa repository è stata realizzata da Massimo Ruggiero, come parte del lavoro di tesi triennale in Ingegneria Informatica.
