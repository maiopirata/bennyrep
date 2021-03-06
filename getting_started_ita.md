# Installazione computer Ubuntu
Questi step preparatori possono prendere anche 1 pomeriggio. Qualsiasi ingeniere o smanettone ti puo` aiutare!

Per prima cosa dobbiamo riuscire a creare un ambiente che permetta a Benny di sperimentare senza problemi.

Per incominciare installiamo ubuntu in un computer dedicato. Su questo computer installiamo ubuntu, che ci permetterà di accedere a distanza al computer se necessario e di giocare con alcuni strumenti di Linux.

Per installare ubuntu scarica questo [file](www.ubuntu.com/download/desktop).
Se il computer è troppo vecchio (diciamo più di 5 anni) potrebbe non esere abbastanza potente, ma generalmente è un problema raro. Una volta finito il download avrai un file .iso nella tua cartella di donwload.

Ora bisogna salvare ubuntu in una chiavetta usb rendendola 'bootable'. Segui le istruzioni in [questa pagina](http://www.ubuntu.com/download/desktop/create-a-usb-stick-on-windows) e non dovresti avere problemi.

Per ultima cosa dobbiamo installare ubuntu nel computer. Salva tutti i dati che non vuoi perdere prima di procedere.

Spegni il computer dove vuoi installare ubuntu e appena acceso stai pronta a schiacciare F1, F2, F3, il tasto delete, esc. Schiaccia questi tasti tutti insieme a meno che tu sappia già quale di questi tasti ti permette di entrare nel BIOS del computer.

Una volta di fronte alla schermata blu del bios (che sembra l'immagine seguente):
![BiosImage](images/bios.png)

Navigando tra le opzioni con le frecce troverai una specifica che dice "First Boot Device" o "Order of Boot ..". L'importante è la parola "boot", che stabilisce dove il cervello del computer guarderà per primo per caricare il sistema.
![BiosOptions](images/bios2.png)

Scegli la chiave Usb come primo boot (qualche volta chiamata removable device o simili...)

Una volta fatta questa modifica, inserisci la chiave usb con ubuntu e premi il tasto "save & exit".

Il computer si riavvia e ti porterà ad installare ubuntu! Ora sarà un computer perfetto per sperimentare un po' di programmazione. 