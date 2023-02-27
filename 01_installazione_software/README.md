# Utilizzo e installazione software
Questa è una guida per utilizzo e installazione del software necessario allo svolgimento dei laboratori. Seguire le istruzioni nell'ordine indicato per evitare problemi.

## Usare il terminale
Su MAC e Linux è presente l'applicativo Terminal (o simili) che lancia un terminale. Su Windows l'applicativo da usare è PowerShell. Il terminale ha impostato il percorso alla vostra cartella home. Per avviarlo in una specifica cartella fare come segue:

- Per MAC da finder fare tasto destro su una cartella, andare su *Servizi* e poi su *Nuovo terminale alla cartella*.

- Per Windows dal file explorer premere shift in contemporanea al tasto destro di modo da far comparire la voce *Apri finestra PowerShell qui*

Per provare, lanciare i seguenti comandi:
``` bash
 ls # mostra contenuto cartella
 cd nome_cartella # si sposta nella cartella
 cd .. # si sposta nella cartella padre
 ```

## Python
Scaricare python dal seguente [link](https://www.python.org/downloads/release/python-3910/). Al fondo della pagina trovate i link al download per i diversi sistemi operativi.

Selezionare le versioni 64 bit, a meno che il vostro sistema non sia a 32 bit. Una volta scaricato avviare l'installer.

**IMPORTATE**: mettere la spunta su *"add python to PATH"* (Windows)

Una volta eseguita l'installazione aprire un terminale e digitare il comando:
``` bash
python --version # mosta versione python
python # lancia l'interprete di python, digitare exit() per uscire
```

## Git
Per installare Git seguire le istruzioni al seguente [link](https://git-scm.com/downloads), selezionando il proprio sistema operativo.

#### Windows
Scaricare l'installer (*.exe*) e durante il processo d'installazione lasciare tutte le opzioni a quelle di default.

#### MacOS
L'installazione su mac richiede l'istallazione del packet manager **brew**. Brew a sua volta richiede i *Command Line Tools (CLT) for Xcode*.
Per scaricare i command line tools eseguire da terminale il seguente comando:

``` bash
xcode-select --install
```
Oppure scaricare il pacchetto dal [sito](https://developer.apple.com/download/all/).
Successivamente installare brew:
``` bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
e usare brew per installare git:
``` bash
brew install git
```
### Configurazione

Una volta installato, aprire un terminale e digitare:
``` bash
git -- version # mostra versione git
git --help # mostra tutti i possibili comandi
```

Successivamente configurare git eseguendo i seguenti due comandi:
```bash
git config --global user.email "you@example.com" # mettere email (se vi create un account github usate quella)
git config --global user.name "Your Name" # inserire vostro nome/nickname
```

## PyCharm
Dal [sito web](https://www.jetbrains.com/pycharm/download/) di PyCharm, seguire le istruzioni d'installazione per il vostro sistema operativo. 

La *Community Edition* basta e avanza (questo corso potreste farlo anche usando terminale e Notepad++).

Altrimenti JetBrains permette di [richiedere](https://www.jetbrains.com/community/education/#students) licenze gratuite per studenti.

Creare un progetto e testare un semplice programma per verificare che Python venga trovato da PyCharm.

## Github
Andare su [github](https://github.com/) e creare un account.
Questo verrà utilizzato per:
- Imparare a usare git, che è al giorno d'oggi è fondamentale per lo sviluppo software
- Rende più semplice rispondere a domande da casa su problemi specifici del vostro codice








