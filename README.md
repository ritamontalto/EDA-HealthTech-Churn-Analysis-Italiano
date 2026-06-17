# Analisi Esplorativa dei Dati per una Startup HealthTech

## Sommario 
Le piattaforme di gestione del diabete si basano sul coinvolgimento dei pazienti e sulla loro aderenza a lungo termine per ottenere risultati clinici efficaci. Questo progetto analizza la retention degli utenti, i comportamenti di engagement e i miglioramenti clinici all’interno di un programma terapeutico digitale per il diabete. Utilizzando l’AI, ho creato 2 dataset sintetici contenenti dati di clienti e utenti appartenenti a una ipotetica startup HealthTech. Con SQL e Power BI, ho pulito e trasformato i dati, analizzato le cause di churn, valutato l’efficacia del trattamento e costruito una dashboard interattiva per identificare i fattori associati alla retention degli utenti e al miglioramento degli outcome di salute.

## Business
Una startup HealthTech vuole ridurre l’abbandono dei pazienti (churn) e migliorare il coinvolgimento nel proprio programma terapeutico digitale per il diabete. La retention è fondamentale nelle piattaforme di digital health, perché il coinvolgimento continuo è necessario per ottenere risultati terapeutici a lungo termine. Il team di product management vuole capire:
- Quali segmenti di utenti hanno il rischio di churn più alto?
- L’engagement influenza la retention?
- Gli utenti mostrano miglioramenti misurabili durante il programma?
- Quali fattori operativi sono associati a una migliore retention?

## Metodologia
1. Pulizia e preparazione dei dati: query SQL per estrarre, pulire e trasformare i dati dal database.
2. Analisi esplorativa (EDA): query SQL per selezionare dati utili a rispondere alle domande di business.
3. Sviluppo dashboard: dashboard in Power BI per visualizzare retention, efficacia del trattamento e insight operativi tramite grafici, schede e filtri interattivi.

## Competenze
SQL: PostgreSQL, CTE, funzioni finestra, join, CASE, aggregazioni, data cleaning
Power BI: modellazione dati, misure DAX, colonne calcolate, dashboard interattive, visualizzazione dati
Analisi: analisi esplorativa, definizione KPI, generazione di insight di business

## Risultati & Suggerimenti
L’analisi mostra che engagement, retention e miglioramenti clinici sono strettamente collegati. Migliorare le strategie di coinvolgimento e identificare precocemente gli utenti a rischio churn può aumentare l’aderenza al programma e massimizzare i risultati per i pazienti.

### Quali segmenti di utenti hanno il rischio di churn più alto?
Il churn è concentrato in specifici segmenti di utenti, in particolare tra quelli con livelli di engagement più bassi e in determinati gruppi demografici.

*Raccomandazioni*

- Identificare precocemente gli utenti a rischio tramite il monitoraggio dell’engagement.
- Introdurre strategie di retention mirate come comunicazioni personalizzate e supporto all’onboarding.

### L’engagement influenza la retention?

Gli utenti con maggiore engagement mostrano una retention più alta, suggerendo che l’interazione costante con la piattaforma è un driver importante per l’aderenza a lungo termine.

*Raccomandazioni*

- Migliorare le funzionalità di onboarding e engagement.
- Usare i livelli di attività come indicatore precoce del rischio di churn.

### Gli utenti mostrano miglioramenti misurabili durante il programma?

L’analisi evidenzia miglioramenti nei principali indicatori di salute, inclusi HbA1c e parametri glicemici, con differenze tra gruppi diagnostici e livelli di engagement.

*Raccomandazioni*

- Incentivare la partecipazione continua al programma per massimizzare i benefici clinici.
- Usare il tracking dei progressi per supportare motivazione e aderenza dei pazienti.

### Quali fattori operativi sono associati a una migliore retention?

Le performance di retention variano in base ai canali di acquisizione e ai piani di trattamento, suggerendo che il percorso utente e la strategia di acquisizione influenzano l’engagement a lungo termine.

*Raccomandazioni*

- Valutare i canali di acquisizione in base alla qualità della retention, non solo al volume di utenti.
- Ottimizzare onboarding ed esperienza di trattamento per i gruppi con churn più elevato.

## File del progetto
- Data: dataset sintetici originali e tabelle pulite pronte per l’analisi
- Power BI: dashboard interattive su retention, outcome e operazioni
- SQL: query per pulizia dati e analisi esplorativa
- Screenshots: anteprime delle dashboard interattive Power BI
