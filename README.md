🚀 MACRO STRUTTURA CATIA V5

Raccolta di macro in VBScript (.catvbs) per CATIA V5 (R19 e successive) progettate per automatizzare la creazione di assiemi, la gestione dei componenti, la struttura dei codici e dei Part Number all'interno dei tuoi progetti CAD.

📋 Indice

    Descrizione delle Macro

    Requisiti

    Installazione e Configurazione

    Autore

🔍 Descrizione delle Macro

Questo repository contiene script automatizzati per accelerare le operazioni ripetitive in ambiente CATIA:

    ProdottoMacro (xyzNivek - CATIA R19)

        Funzione principale: Genera un nuovo documento di tipo CATProduct partendo da zero tramite un input utente, impostando automaticamente il PartNumber principale (es. -00-00), inserendo una parte di asse con suffisso -axs applicando i vincoli di fissaggio (Fix).

    GruppoMacro (xyzNivek - CATIA R19)
        
        Funzione principale: Genera un nuovo documento di tipo CATProduct basato sul nome del componente principale (es. estraendo la base con suffisso -00-00) e genera automaticamente una parte associata con suffisso -axs, applicando i vincoli di fissaggio (Fix).

    ParteMacro (xyzNivek - CATIA R19)
        
        Funzione principale: Genera un nuovo documento di tipo CATPart nel sotto-prodotto basato sul nome del prodotto selezionato (es. estraendo la base con suffisso -00-00).


🛠️ Requisiti

    Software CAD: CATIA V5 (ENG)

⚙️ Installazione e Configurazione

Per installare ed eseguire le macro in CATIA V5:

    Clona o scarica il repository (o copia il codice dei file .catvbs).

👤 Autore

    Kevin — xyzEkvi
