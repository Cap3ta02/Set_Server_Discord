# Set_Server_Discord
Questa è una guida in italiano, per poter gestire il vostro canale discord in maniera totalmente automatica, senza bisogno di nessun moderatore o bot esterni.

## Guida alla Creazione di una Community su Discord e Bot Personalizzato

Benvenuti nella nostra guida dedicata a coloro che vogliono avviare la propria community su Discord e creare un bot personalizzato in Python. Questo README fornisce istruzioni dettagliate per configurare l'Automod su Discord e programmare un bot per arricchire l'esperienza dei vostri utenti.

## Configurazione dell'Automod su Discord

### Passo 1: 
- Facendo tasto destro , potremmo cliccare sulla voce " Impostazioni del Server ", dirigendoci nella categoria `Moderazione`.

### Configurazione di Sicurezza

-Queste impostazioni riguarda nel particolare, il nuovo utente. Il problema principale dei canali discord, sono gli spam, ovvero, utenti falsi gestiti da script, che attraverso id dei canali, inviano dei messaggi spam sulle chat testuali. Il mio consiglio è di impostare la voce  `Livello di verifica` su `massimo`. Ovvero , l'utente dovrà avere il suo profilo verificato da un numero di cellulare.

- Impostare il filtro per immagini esplicite sulla voce `Filtra i messaggi di tutti i membri`

### Automod

- All'interno della sezione Automod, avremmo la funzione di monitorare i messaggi dei nostri utenti, avendo la possibilità di evitare lo spam di menzioni come `@tag` e di decidere come sanzionare lo spam, che sia eliminando il messaggio o avvertendo direttamente l'utente.

Questa parte risulta particolarmente interessante, in quanto consente di bloccare specifiche parole inviate dagli utenti avendo la possibilità di personalizzare l'inserimento di parole, decidendo quali non desideriamo visualizzare nel nostro server.

### Registro Attività e Ban

- Monitorare tutte le attività degli utenti sul server.
- Consultare la lista di utenti bannati.

## Programmazione del Bot Discord

Se desiderate arricchire il vostro server Discord con funzionalità personalizzate, potete creare un bot anche senza esperienza di programmazione. Seguite questi passaggi:

### Passo 1: Attivare la Modalità Sviluppatore su Discord

- Impostazioni utente -> "Avanzate" -> Abilitate la "Modalità per sviluppatori".

### Passo 2: Creare un Bot su Discord Developer Portal

1. Visitate [Discord Developer Portal](https://discord.com/developers/applications) e effettuate il login con il vostro account discord.
2. Cliccate su `New Application` e inserite il nome del vostro bot.
3. Dopo aver inserito il nome, vi uscirà il pannello di controllo del vostro bot, dove potrete personalizzare descrizione,nome,icona del bot

### Passo 3: Ottenere il Token del Bot

- Nella sezione "Bot", della colonnina di sinistra del pannello di controllo, cliccate su "Reset Token" e copiate il token del vostro bot.

### Passo 4: Impostare il Bot con il Codice

- Seguite la guida nel file "bot.py" nella repository, con commenti esplicativi su ogni passo e funzionamento.

Con questi passaggi, sarete in grado di configurare l'Automod su Discord e programmare un bot personalizzato per la vostra community. Benvenuti nel mondo della gestione avanzata dei server Discord!
