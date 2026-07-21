# Analisi Esplorativa dei Dati per una startup HealthTech

## Sommario 
Le piattaforme di gestione del diabete si basano sul coinvolgimento dei pazienti e sulla continuità nel tempo del trattamento per ottenere risultati clinici efficaci. Questo progetto analizza la conservazione degli utenti, i comportamenti di engagement e i miglioramenti clinici all’interno di un ipotetico programma terapeutico digitale per il diabete. Per simulare un ambiente aziendale realistico, sono stati creati 2 dataset sintetici contenenti informazioni sui clienti e sugli utenti di una startup HealthTech fittizia. Utilizzando SQL e Power BI ho pulito e trasformato i dati, analizzato le cause di abbandono, valutato l’efficacia del trattamento e costruito una dashboard interattiva per identificare i fattori associati alla conservazione degli utenti e al miglioramento degli esiti clinici.


## Problema Aziendale
Una startup HealthTech vuole ridurre l’abbandono dei pazienti e migliorarne il coinvolgimento nel proprio programma terapeutico digitale per la gestione del diabete. La conservazione dei pazienti è fondamentale per le piattaforme digitali di questo tipo, perché il coinvolgimento continuo è necessario per ottenere risultati terapeutici efficaci nel lungo periodo. Il team di Product Management vuole comprendere:
- Quali segmenti di utenti hanno il rischio di abbandono più alto?
- Il coinvolgimento influenza la conservazione degli utenti?
- Gli utenti mostrano miglioramenti misurabili durante il programma?
- Quali fattori operativi sono associati a una migliore conservazione di utenti?


## Metodologia

```
Dati grezzi
   ↓
Pulizia e validazione dati
   ↓
Analisi esplorativa dei dati
   ↓
Dashboard interattiva Power BI
   ↓
Insight aziendali e raccomandazioni
```

Ogni fase del workflow è descritta di seguito

**Pulizia e preparazione dei dati**

I dati grezzi sono stati estratti, puliti, standardizzati e trasformati in dataset pronti per l’analisi. Le attività svolte includono:

- Gestione dei duplicati
- Trattamento dei valori mancanti
- Standardizzazione dei formati disomogenei
- Risoluzione di problemi relativi alla qualità dei dati 

**Analisi Esplorativa dei Dati (EDA)**
- Analisi delle principali domande relative a conservazione degli utenti, coinvolgimento ed efficacia del trattamento
- Valutazione delle performance operative attraverso aggregazioni, segmentazioni e analisi dei KPI

**Sviluppo Dashboard Interattiva**
- Creazione di dashboard interattive con KPI card, confronti visivi e filtri dinamici per supportare decisioni basate sui dati
- Progettazione di 3 pagine di reporting dedicate alle principali aree analitiche: analisi della conservazione, efficacia del trattamento, performance operative


## Competenze 

**Analytics**
- Analisi Esplorativa dei Dati (EDA)
- Definizione delle domande di business
- Sviluppo KPI
- Generazione di insight
- Suggerimenti basati sui dati

**SQL (PostgreSQL)**
- Pulizia dati
- Validazione dati
- CTE
- Window Functions
- Join
- CASE Statement
- Aggregations
- Analisi esplorativa dei dati

**Power BI**
- Modellazione dati
- Misure DAX
- Dashboard interattive
- Sviluppo KPI
- Data visualization

**Sviluppo Assistito dall’AI**
- Generazione dataset sintetici (ChatGPT)
- Supporto al brainstorming analitico


## Datasets
I dataset utilizzati in questo progetto sono stati generati sinteticamente e non contengono informazioni reali sui pazienti né dati personali identificabili. Sono stati creati con il supporto dell’AI per finalità di portfolio, progettati per simulare un ambiente realistico di digital healthcare e replicare intenzionalmente problematiche comuni nella gestione dei dati sanitari, tra cui incongruenze, valori mancanti, record duplicati e problemi di formattazione. L’AI è stata utilizzata esclusivamente per generare dati fittizi destinati all’analisi. Tutte le attività di pulizia dati, query SQL, logica business, analisi esplorativa, misure DAX, progettazione dashboard e insight finali sono state sviluppate, verificate e implementate autonomamente da me.


## Risultati & Suggerimenti
L’analisi mostra che engagement, conservazione e miglioramenti clinici sono strettamente collegati. Migliorare le strategie di coinvolgimento e identificare precocemente gli utenti a rischio di abbandono può aumentare l’aderenza al programma e massimizzare i risultati per i pazienti.

### Quali segmenti di utenti hanno il rischio di abbandono più alto?
L'abbandono è concentrato in specifici segmenti di utenti, in particolare tra quelli con livelli di engagement più bassi e in determinati gruppi demografici.

*Suggerimenti*

- Identificare precocemente gli utenti a rischio tramite il monitoraggio dell’engagement.
- Introdurre strategie di conservazione mirate, come comunicazioni personalizzate e supporto all’onboarding.

### Il coinvolgimento influenza la conservazione degli utenti?

Gli utenti con maggiore engagement mostrano una conservazione più alta, suggerendo che l’interazione costante con la piattaforma è un fattore importante per l’aderenza a lungo termine.

*Suggerimenti*

- Migliorare le funzionalità di onboarding e engagement.
- Usare i livelli di attività come indicatore precoce del rischio di abbandono.

### Gli utenti mostrano miglioramenti misurabili durante il programma?

L’analisi evidenzia miglioramenti nei principali indicatori di salute, inclusi HbA1c e parametri glicemici, con differenze tra gruppi diagnostici e livelli di engagement.

*Suggerimenti*

- Incentivare la partecipazione continua al programma per massimizzare i benefici clinici.
- Usare il tracking dei progressi per supportare motivazione e aderenza dei pazienti.

### Quali fattori operativi sono associati a una migliore conservazione degli utenti?

Le performance di conservazione degli utenti variano in base ai canali di acquisizione e ai piani di trattamento, suggerendo che il percorso utente e la strategia di acquisizione influenzano l’engagement a lungo termine.

*Suggerimenti*

- Valutare i canali di acquisizione in base alla qualità della conservazione, non solo al volume di utenti.
- Ottimizzare onboarding ed esperienza di trattamento per i gruppi con tasso di abbandono più elevato.


## Cartelle e File 
- Data: dataset sintetici originali e dataset puliti, pronti per l’analisi
- Power BI: dashboard interattive su conservazione, efficacia del trattamento e analisi operativa
- SQL: pulizia dati e analisi esplorativa, inclusivi di query e note
- Screenshots: anteprime delle dashboard interattive Power BI
