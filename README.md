# PROGETTO UNIVERSITARIO BASI DI DATI
Il presente progetto consiste nello sviluppo di un database relazionale per la gestione di una piattaforma musicale, implementato utilizzando PostgreSQL. L'obiettivo è progettare un sistema efficiente per archiviare, organizzare e analizzare i dati relativi agli utenti, agli album, alle tracce e agli ascolti, garantendo integrità e sicurezza attraverso l'uso di vincoli, funzioni e trigger.

Il database permette di gestire due tipologie di utenti: ascoltatori e artisti, con regole specifiche che ne disciplinano le operazioni. Gli artisti possono pubblicare album e tracce, che possono essere classificate come originali, remastering o cover. Il sistema implementa vincoli per garantire la correttezza dei dati, come il formato delle e-mail, le date di nascita valide e la possibilità di creare contenuti solo da parte di utenti autorizzati.

Per migliorare la gestione delle informazioni e l’analisi dei dati, il database include funzioni avanzate che consentono di ottenere statistiche sugli artisti più ascoltati, le tracce più riprodotte e gli orari con maggiore attività di ascolto. Inoltre, vengono gestite le relazioni sociali tra utenti attraverso un sistema di follower, che permette di monitorare le interazioni tra gli ascoltatori.

L’implementazione prevede anche l’uso di trigger e funzioni PL/pgSQL, per automatizzare operazioni critiche, come la crittografia delle password, l’assegnazione automatica della data di iscrizione e l'aggiornamento delle versioni delle tracce in caso di remastering.

Grazie all'uso di chiavi primarie, chiavi esterne e controlli di integrità, il database garantisce la consistenza dei dati, mentre le procedure e funzioni personalizzate offrono un livello avanzato di analisi e gestione delle informazioni, rendendo il sistema scalabile e sicuro.
