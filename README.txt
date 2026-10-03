IL MIO RICETTARIO — PWA / CONDIVIDI DA ANDROID

Questa versione aggiunge la struttura PWA e il ricevitore Web Share Target.

FUNZIONA:
- installazione come PWA quando pubblicata su HTTPS o eseguita su localhost;
- ricezione di titolo/testo/link condivisi tramite il menu Condividi del sistema, quando browser e dispositivo supportano Web Share Target;
- apertura automatica della finestra Importa con i dati ricevuti;
- analisi del testo già presente e compilazione della bozza;
- salvataggio locale delle ricette.

NON E' ANCORA COLLEGATO:
- recupero automatico della caption da Instagram partendo dal solo URL;
- download/trascrizione automatica dell'audio del Reel;
- backend AI per trasformare automaticamente il contenuto del Reel in ricetta.

TEST SU PC:
1. Aprire PowerShell nella cartella.
2. Eseguire: py -m http.server 8000
3. Aprire: http://localhost:8000

Per il test Android serve una pubblicazione HTTPS. Una volta pubblicata e installata, si potrà provare Instagram -> Condividi -> Ricettario.
