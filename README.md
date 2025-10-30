# Istruzioni installazione Master 2026
### In questa pagina troverete istruzioni e file per installare un ambiente minimale per l'edizione 2026 del Master in Big Data e Social Analytics. Non dovrebbe richiedervi più di un'ora per completare tutto. Vi preghiamo di leggere le istruzioni per intero prima di iniziare la procedura. Le istruzioni sono sia in italiano che in inglese. Per scaricare tutti i file, incluso questo readme, cliccate sul bottone verde "<> Code", e poi su "Download ZIP".

Gentili studentesse e gentili studenti,
 
al fine di prepararvi al meglio per l'inizio delle lezioni e non incorrere in problemi tecnici abbiamo preparato questa guida (densa di istruzioni), con lo scopo di fornirvi i dettagli per poter installare i software necessari prima dell'inizio dei corsi.
 
In questa guida NON sono presenti informazioni relative al software da far girare su Windows, ovvero Sql Management Studio, che riceverete in seguito.
  
## ATTENZIONE: LEGGERE TUTTE LE ISTRUZIONI ATTENTAMENTE PRIMA DI PROSEGUIRE.

- **Installazione ANACONDA**
Anaconda è una piattaforma open-source contenente vari pacchetti e software che utilizzeremo durante il master.
Trovate il software al seguente link:
https://www.anaconda.com/products/individual
Installate la versione individuale (individual) di anaconda. Abbiate cura di selezionare correttamente il vostro sistema operativo (dovrebbe essere riconosciuto automaticamente, in ogni caso, al link sopra, trovate tutti i pacchetti per qualsiasi sistema operativo) **Per favore, installate da 0 una nuova versione di Anaconda. Il nuovo solver libmamba è ora il predefinito nelle nuove versioni/installazioni. Se hai già un'installazione precedente di Anaconda, aggiornatela o reinstallatela da zero.** Maggiori informazioni qui: https://www.anaconda.com/blog/a-faster-conda-for-a-growing-community

- **Installazione PYCHARM**
Pycharm è un ambiente di sviluppo. L'equivalente di Word per scrivere programmi.
Trovate il software al seguente link:
https://www.jetbrains.com/pycharm/download/
La versione da installare è la Community (free e open source). Anche qui, state attenti a scegliere l’installer corretto per il vostro sistema operativo.

- **Installazione Environment Master**
Dopo l'installazione di Anaconda, potrete avviare Anaconda-Navigator che è un'interfaccia grafica per aprire i vari software. Seguendo il video tutorial allegato e dopo aver scaricato il file .yml allegato, utilizzate il file .yml per installare i pacchetti python di cui avrete bisogno. Seguite il tutorial video per indicazioni puntuali. Fate questo solo DOPO aver correttamente installato Anaconda. Il comando da eseguire, e che trovate anche nel video, è: <code>conda env create -v -f env_master_2026.yml</code>
La fase di installazione potrebbe richiedere un tempo variabile a seconda del vostro computer. Attendete pazientemente. Mentre l'installazione è in corso NON spegnere il PC o disconnettere da rete o corrente.
 
- **Test Environment Master**
Dopo la suddetta installazione, per testare l’environment master potete aprire un terminale (terminal su Mac o Windows Terminal su windows) e navigare fino alla cartella dove avete salvato il file test_master.py utilizzando il comando: cd [nome_cartella]. Guardate il video per avere un esempio di tale comando. Una volta arrivati nella cartella contenente il file, digitate: <code>conda activate env_master_2026</code> premere invio, poi digitare <code>python test_master.py</code>
Se l’installazione è stata compiuta correttamente, vedrete apparire sul terminale la scritta "Hello World” (ci vorrà qualche minuto).
 
- **Studio Preliminare Python (questa attività NON è obbligatoria)**
Per quelli che fossero interessati a iniziare a studiare Python da autodidatti vi consigliamo il libro online e open source disponibile al link:
http://www.spronck.net/pythonbook/
SoBigData accademy course

- **DBeaver**
DBeaver è un software per la gestione di basi di dati. Per scaricarlo cliccare sul seguente link: https://dbeaver.io/download/
E selezionare la versione adatta al proprio Sistema Operativo. Proseguite dunque con le normali procedure di installazione di un qualsiasi software.
Ci vediamo agli installation days, per verificare la corretta installazione ed eventualmente aiutarvi se avete problemi.

- **Jekyll**
Nel corso LBDAI – Laboratory of Big Data and Artificial Intelligence for Society utilizzeremo Jekyll, uno Static Site Generator (SSG) open-source che consente di creare siti web statici, veloci e facilmente gestibili, senza la necessità di database o backend complessi.

Jekyll è scritto in Ruby, ma non è necessario conoscere Ruby per utilizzarlo: serve solo che sia installato sul proprio computer.  
Per installare jekyll seguita la guida che potete trovare qui: https://danielefadda.github.io/master-projects-template-2026/local-development-eng.html

------------------------------------------------------------------------------------------------------------------------------------------


# Master 2026 Installation Instructions (English)
### In this page you will find instructions and files to install a minimal environment for the 2026 edition of the Master in Big Data and Social Analytics. It should not take you more than an hour to complete everything. Please reade the instructions in full before starting the procedure. Instructions are found both in english and italian. To download all the files, including this readme, click on the "<> Code" green button, then on the "Download ZIP" option.

Dear Students,

To best prepare for the start of classes and avoid technical issues, we have prepared the following guide (dense with instructions) to provide you with details on how to install the necessary software before the courses begin.

This guide does NOT contain information regarding software for Windows, namely Sql Management Studio, which you will receive later.

## ATTENTION: READ ALL INSTRUCTIONS CAREFULLY BEFORE PROCEEDING.

- **Installing ANACONDA** Anaconda is an open-source platform containing various packages and software that we will use during the master’s program. You can find the software at the following link: https://www.anaconda.com/products/individual Install the individual version of Anaconda. Be sure to correctly select your operating system (it should be automatically recognized, but in any case, the above link contains packages for all operating systems). **Please, install a new, fresh version of Anaconda. The new lib-mamba solver comes by default with new version/installations. If you already have an older Anaconda installation, please update it or re-install from 0** More info here: https://www.anaconda.com/blog/a-faster-conda-for-a-growing-community
- **Installing PYCHARM** Pycharm is a development environment, akin to Word for writing programs. You can find the software at the following link: https://www.jetbrains.com/pycharm/download/ Install the Community version (free and open source). Again, make sure to select the correct installer for your operating system.
- **Master Environment Installation** After installing Anaconda, you can launch the Anaconda-Navigator, which is a graphical interface for opening various software. Following the attached video tutorial and after downloading the attached .yml file, use the .yml file to install the necessary Python packages. Follow the video tutorial for detailed instructions. Do this ONLY AFTER correctly installing Anaconda. The command to execute, as shown in the video, is: <code>conda env create -v -f env_master_2026.yml</code>. The installation process may take varying amounts of time depending on your computer. Please be patient. During installation, DO NOT turn off your PC or disconnect from the network or power source.
- **Testing the Master Environment** After the aforementioned installation, to test the master environment, you can open a terminal (Terminal on Mac or Windows Terminal on Windows) and navigate to the folder where you saved the test_master.py file using the command: cd [folder_name]. Watch the video for an example of this command. Once in the folder containing the file, type: <code>conda activate env_master_2026</code>, press enter, then type <code>python test_master.py</code>. If the installation was successful, you will see "Hello World" appear on the terminal (this may take a few minutes).
- **Preliminary Python Study** (this activity is OPTIONAL) For those interested in starting to learn Python independently, we recommend the online and open-source book available at the link: http://www.spronck.net/pythonbook/ SoBigData Academy Course
- **DBeaver** DBeaver is software for database management. To download it, click the following link: https://dbeaver.io/download/ Select the version suitable for your operating system and proceed with the usual software installation procedures. We will see you at the installation days to verify the correct installation and assist you if you encounter any issues.
- **DBeaver** DBeaver is software for database management. To download it, click the following link: https://dbeaver.io/download/ Select the version suitable for your operating system and proceed with the usual software installation procedures. We will see you at the installation days to verify the correct installation and assist you if you encounter any issues.







