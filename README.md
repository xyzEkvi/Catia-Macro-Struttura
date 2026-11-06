🚀 MACRO STRUTTURA CATIA V5

Raccolta di macro in VBScript (.catvbs) per CATIA V5 (R19 e successive) progettate per automatizzare la creazione di assiemi, la gestione dei componenti, la struttura dei codici e dei Part Number all'interno dei tuoi progetti CAD.

📋 Indice

    Descrizione delle Macro

    Requisiti

    Installazione e Configurazione

    Guida all'Utilizzo

    Autore

🔍 Descrizione delle Macro

Questo repository contiene script automatizzati per accelerare le operazioni ripetitive in ambiente CATIA:

    Macro Gestione Gruppo e Assieme (xyzEkvi - CATIA R19)

        Funzione principale: Automatizza la creazione di un sotto-prodotto basato sul nome del componente principale (es. estraendo la base con suffisso -00-00) e genera automaticamente una parte associata con suffisso -axs, applicando i vincoli di fissaggio (Fix) e ripulendo le istanze (gestione del suffisso .1).

    Macro Creazione Assieme Principale (xyzNivek - CATIA R19)

        Funzione principale: Genera un nuovo documento di tipo CATProduct partendo da zero tramite un input utente, impostando automaticamente il PartNumber principale (es. -00-00), inserendo una parte di asse con suffisso -axs e bloccandola nello spazio.

🛠️ Requisiti

    Software CAD: CATIA V5 (testato e ottimizzato per la versione R19).

⚙️ Installazione e Configurazione

Per installare ed eseguire le macro in CATIA V5:

    Clona o scarica il repository (o copia il codice dei file .catvbs).

    Apri CATIA V5.

    Accedi al menu degli script: vai su Strumenti > Macro > Macro... (oppure premi la scorciatoia da tastiera Alt + F8).

    Fai clic su Visual Basic Editor se desideri incollare il codice direttamente in un modulo, oppure seleziona la libreria esistente dove hai salvato i file delle macro.

🎮 Guida all'Utilizzo

    Apri un documento CATProduct attivo in CATIA (per la macro di gestione gruppi).

    Premi Alt + F8 per aprire la finestra delle macro o installa una toolbar a tuo piacimento.

    Seleziona la macro desiderata dall'elenco ed esegui (Run).

    Inserisci i dati richiesti tramite i riquadri di dialogo (InputBox) a schermo.

👤 Autore

    Kevin — xyzEkvi
