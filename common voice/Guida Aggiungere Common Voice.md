# AGGIUNGERE NUOVE FRASI, REVISIONARE QUELLE GIA' PRESENTI SU COMMON VOICE O SEGNALARE ERRORI
 

### Linee guida per la revisione ed esempio pratico
https://github.com/Sav22999/Articoli-Post-mozilla-italia/blob/voice-web/common%20voice/Linee%20guida%20revisione%20Common%20Voice.md

---------------------------

In questa guida vedremo come è possibile, facilmente, aggiungere nuove frasi su Common Voice o revisionare quelle già presenti. 
### Aggiungere frasi

## Aggiungere frasi (Metodo 1) 

Recarsi sul repository di MozillaItalia su GitHub: “voice-web” (https://github.com/MozillaItalia/voice-web). 

Dopodiché è necessario creare un fork proprio di questo progetto e, successivamente, lavorare su quel fork (si noti che è necessario utilizzare il branch "ita-review" e non "master"). 

Recarsi sul proprio fork UserName/voice-web, spostarsi nel ramo (branch) ita-review ed aggiungere le frasi che si desiderano nel file txt presente in “voice-web\server\data\it\frasi.txt” alla fine del documento, ricordando le “regole di stile” (sopra riportate) e, importante, ricordare che la licenza dei contenuti deve essere LIBERA, quindi CC0, +70life, e così via (se la licenza non è riportata NON inserire quelle determinate frasi). 

Dopo aver inserito tutte le frasi, dopo averle revisionate in toto è possibile procedere alla pull request, effettuare il merge del proprio fork (quindi del repository su cui si è lavorati fino ad ora) con quello di MozillaItalia. 

Nella descrizione della pr inserire la fonte delle frasi in modo tale da effettuare le dovute verifiche. 

### Aggiungere frasi (Metodo 2) – Consigliato per i meno esperti o per chi non ha familiarità con GitHub 

Recarsi sul repository di MozillaItalia su GitHub “voice-web” e aprire un ticket (issue) inserendo sia le frasi da inserire, sia la fonte dalla quale sono state prese. 

### Aggiungere frasi (Metodo 3) 

Inviare le frasi da aggiungere (con la relativa fonte) a @Sav22999 tramite Telegram che procederà ad aggiungerle (dopo averle revisionate). 

### Revisionare frasi già esistenti 

Eseguire la stessa procedura dell’inserimento di nuove frasi, tuttavia è necessario cercare la (o le) frase desiderata tramite funzioni specifiche (“Trova...” o “Cerca...”).

### Segnalare errori
Per segnalare un errore di ordine generale nella scrittura delle frasi (mancanza di lettere, lettere errate, punteggiatura errata/doppie virgole/..., parole errate, ecc.) è sufficiente SALTARE LA FRASE (quindi non registrarla) e creare un nuovo ISSUE su GitHub (qui)[https://github.com/MozillaItalia/voice-web/issues] inserendo la frase completa errate seguita dalla frase completa corretta (con le correzioni).
Se non si sa utilizzare GitHub, non c'è problema! Mozilla Italia ti dà la possibilità anche di segnalare la frase direttamente nel gruppo "Home" o, in alternativa, in privato a @Mte90 o a @Sav22999.
