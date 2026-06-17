# Analisi Esplorativa dei Dati per una startup HealthTech

## Sommario 
Le piattaforme di gestione del diabete si basano sul coinvolgimento dei pazienti e sulla loro aderenza a lungo termine per ottenere risultati clinici efficaci. Questo progetto analizza la conservazione degli utenti, i comportamenti di engagement e i miglioramenti clinici all’interno di un programma terapeutico digitale per il diabete. Utilizzando l’AI, ho creato 2 dataset sintetici contenenti dati di clienti e utenti appartenenti a un'ipotetica startup HealthTech. Con SQL e Power BI ho pulito e trasformato i dati, analizzato le cause di abbandono, valutato l’efficacia del trattamento e costruito una dashboard interattiva per identificare i fattori associati alla conservazione degli utenti e al miglioramento delle condizioni di salute.

## Problema del Business
Una startup HealthTech vuole ridurre l’abbandono dei pazienti e migliorarne il coinvolgimento nel proprio programma terapeutico digitale per il diabete. La conservazione degli utenti è fondamentale nelle piattaforme digitali di questo tipo, perché il coinvolgimento continuo è necessario per ottenere risultati terapeutici a lungo termine. Il team di product management vuole capire:
- Quali segmenti di utenti hanno il rischio di abbandono più alto?
- Il coinvolgimento influenza la conservazione degli utenti?
- Gli utenti mostrano miglioramenti misurabili durante il programma?
- Quali fattori operativi sono associati a una migliore conservazione di utenti?

## Metodologia
1. Pulizia e preparazione dei dati: query SQL per estrarre, pulire e trasformare i dati dal database.
2. Analisi esplorativa (EDA): query SQL per selezionare dati utili a rispondere alle domande e al problema del business.
3. Sviluppo dashboard: dashboard in Power BI per visualizzare conservazione, efficacia del trattamento e insight operativi tramite grafici e filtri interattivi.

## Competenze
SQL: PostgreSQL, CTEs, Window functions, Joins, Case statements, Aggregations, Data cleaning
Power BI: Data modeling, DAX, Dashboard interattive, Data visualization
Analisi: analisi esplorativa, definizione KPI, generazione di business insights

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
- SQL: query per pulizia dei dati e analisi esplorativa
- Screenshots: anteprime delle dashboard interattive Power BI
