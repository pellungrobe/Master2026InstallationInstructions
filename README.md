# Istruzioni installazione Master 2027
### In questa pagina troverete istruzioni e file per installare un ambiente minimale per l'edizione 2027 del Master in Big Data Analytics & AI for Society. Non dovrebbe richiedervi più di un'ora per completare tutto. Vi preghiamo di leggere le istruzioni per intero prima di iniziare la procedura. Le istruzioni sono sia in italiano che in inglese. Per scaricare tutti i file, incluso questo readme, cliccate sul bottone verde "<> Code", e poi su "Download ZIP".

Gentili studentesse e gentili studenti,

al fine di prepararvi al meglio per l'inizio delle lezioni e non incorrere in problemi tecnici abbiamo preparato questa guida, con lo scopo di fornirvi i dettagli per poter installare i software necessari prima degli Installation Days. Seguite i passaggi nell'ordine indicato.

In questa guida NON sono presenti informazioni relative a SQL Server Management Studio, che riceverete separatamente.

## ATTENZIONE: LEGGERE TUTTE LE ISTRUZIONI ATTENTAMENTE PRIMA DI PROSEGUIRE.

- **1. Installazione PYCHARM**
PyCharm è un ambiente di sviluppo per scrivere ed eseguire programmi Python.
Trovate il software al seguente link: https://www.jetbrains.com/pycharm/download/
Scaricate PyCharm per il vostro sistema operativo e completate l'installazione. Per le attività del Master sono sufficienti le funzionalità gratuite.

- **2. Installazione uv**
**Windows**: aprite PowerShell dal menu Start e installate uv con il comando:
<code>irm https://astral.sh/uv/install.ps1 | iex</code>
**macOS e Linux**: aprite il Terminale e installate uv con il comando:
<code>curl -LsSf https://astral.sh/uv/install.sh | sh</code>
Al termine dell'esecuzione del comando, verificate che l'installazione abbia avuto successo leggendo il messaggio sul terminale.

- **3. Creazione Environment Master**
Fate questo solo DOPO aver correttamente installato uv (passaggio 2).
Aprite cmd su Windows o il Terminale su macOS e Linux. Create la cartella master ed entrate al suo interno:
<code>mkdir master2027</code> e poi <code>cd master2027</code>
Installate e fissate Python 3.11, poi create l'ambiente virtuale:
<code>uv python install 3.11</code> e poi <code>uv venv</code>
Salvate il file requirements.txt che trovate in questa repository nella cartella master2027 e installate i pacchetti scrivendo sul terminale:
<code>uv pip install -r requirements.txt</code>
L'installazione può richiedere diversi minuti. Attendete pazientemente. Mentre l'installazione è in corso NON spegnete il PC e NON disconnettetevi dalla rete o dalla corrente.

- **4. Test Environment Master**
Dopo l'installazione, scaricate il file test_master.py da questa repository e salvatelo nella cartella master2027.
Aprite un terminale e spostatevi nella cartella master2027 usando il comando <code>cd master2027</code>
Eseguite il test con il comando: <code>uv run test_master.py</code>
Se la configurazione è corretta, vedrete apparire sul terminale la scritta "Hello World" (ci vorrà qualche minuto).

- **5. DBeaver**
DBeaver è un software per la gestione di basi di dati. Per scaricarlo cliccate sul seguente link: https://dbeaver.io/download/
Scaricate DBeaver Community per il vostro sistema operativo e completate l'installazione seguendo le istruzioni del programma.

- **6. Installazione Ollama (questa attività NON è obbligatoria)**
**Windows**: aprite PowerShell dal menu Start e installate Ollama con il comando:
<code>irm https://ollama.com/install.ps1 | iex</code>
**macOS e Linux**: aprite il Terminale e installate Ollama con il comando:
<code>curl -LsSf https://ollama.com/install.sh | sh</code>
Al termine dell'esecuzione del comando, verificate che l'installazione abbia avuto successo leggendo il messaggio sul terminale.

- **7. Studio Preliminare Python (questa attività NON è obbligatoria)**
Per quelli che fossero interessati a iniziare a studiare Python da autodidatti vi consigliamo il libro online gratuito disponibile al link:
http://www.spronck.net/pythonbook/

- **8. Preparazione agli Installation Days**
Prima degli incontri, cercate di completare tutte le installazioni e di eseguire il test dell'Environment Master.
Ci vediamo agli Installation Days, per verificare la corretta configurazione dei software e aiutarvi in caso di problemi tecnici.

------------------------------------------------------------------------------------------------------------------------------------------


# Master 2027 Installation Instructions (English)
### In this page you will find instructions and files to install a minimal environment for the 2027 edition of the Master in Big Data Analytics & AI for Society. It should not take you more than an hour to complete everything. Please read the instructions in full before starting the procedure. Instructions are available both in English and Italian. To download all the files, including this readme, click on the green "<> Code" button, then on the "Download ZIP" option.

Dear Students,

To best prepare for the start of classes and avoid technical issues, we have prepared the following guide to provide you with details on how to install the necessary software before the Installation Days. Follow the steps in the order shown.

This guide does NOT contain information regarding SQL Server Management Studio, which will be provided separately.

## ATTENTION: READ ALL INSTRUCTIONS CAREFULLY BEFORE PROCEEDING.

- **1. Installing PYCHARM**
PyCharm is a development environment for writing and running Python programs.
You can find the software at the following link: https://www.jetbrains.com/pycharm/download/
Download PyCharm for your operating system and complete the installation. The free features are sufficient for the Master's activities.

- **2. Installing uv**
**Windows**: open PowerShell from the Start menu and install uv with the command:
<code>irm https://astral.sh/uv/install.ps1 | iex</code>
**macOS and Linux**: open Terminal and install uv with the command:
<code>curl -LsSf https://astral.sh/uv/install.sh | sh</code>
Once the command has finished running, check that the installation was successful by reading the message in the terminal.

- **3. Master Environment Installation**
Do this ONLY AFTER correctly installing uv (step 2).
Open cmd on Windows or Terminal on macOS and Linux. Create the master folder and move into it:
<code>mkdir master2027</code> and then <code>cd master2027</code>
Install and pin Python 3.11, then create the virtual environment:
<code>uv python install 3.11</code> and then <code>uv venv</code>
Save the requirements.txt file you find in this repository into the master2027 folder and install the packages by typing in the terminal:
<code>uv pip install -r requirements.txt</code>
The installation may take several minutes. Please be patient. During installation, DO NOT turn off your PC or disconnect from the network or power source.

- **4. Testing the Master Environment**
After the installation, download the test_master.py file from this repository and save it in the master2027 folder.
Open a terminal and move to the master2027 folder using the command <code>cd master2027</code>
Run the test with the command: <code>uv run test_master.py</code>
If the configuration is correct, you will see "Hello World" appear on the terminal (this may take a few minutes).

- **5. DBeaver**
DBeaver is software for database management. To download it, click the following link: https://dbeaver.io/download/
Download DBeaver Community for your operating system and complete the installation by following the program's instructions.

- **6. Installing Ollama (this activity is OPTIONAL)**
**Windows**: open PowerShell from the Start menu and install Ollama with the command:
<code>irm https://ollama.com/install.ps1 | iex</code>
**macOS and Linux**: open Terminal and install Ollama with the command:
<code>curl -LsSf https://ollama.com/install.sh | sh</code>
Once the command has finished running, check that the installation was successful by reading the message in the terminal.

- **7. Preliminary Python Study (this activity is OPTIONAL)**
For those interested in starting to learn Python independently, we recommend the free online book available at the link:
http://www.spronck.net/pythonbook/

- **8. Preparing for the Installation Days**
Before the sessions, try to complete all the installations and run the Master Environment test.
We will see you at the Installation Days to verify that the software is configured correctly and assist you if you encounter any technical issues.
