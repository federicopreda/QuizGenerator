
# QuizGenerator
![Python3](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white) ![UNIMI](https://img.shields.io/badge/UNIMI-004082?style=for-the-badge) [![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/)

 

Benvenuti al Generatore di Quiz dedicato al corso "Aspetti Etici, Legali, Sociali ed Economici dell’Informatica" del dipartimento di informatica dell'Università degli Studi di Milano. Questo strumento è stato progettato per consentirti di creare quiz personalizzati, mettendo in primo piano la tua esperienza di apprendimento. Con questo generatore, puoi:

- **Personalizzare il Tuo Quiz**: Scegli il numero di domande che desideri affrontare e seleziona gli argomenti specifici su cui desideri testare la tua preparazione
- **Visualizzare Risultati Dettagliati**: Alla fine del quiz, avrai accesso a risultati dettagliati. Non solo conoscerai il tuo punteggio complessivo, ma potrai anche esplorare i risultati in profondità attraverso grafici informativi. Questi grafici mostreranno la distribuzione delle domande per argomento e la percentuale di risposte corrette per ciascun argomento.

- **Correzione Automatica**: Non preoccuparti della correzione. Questo generatore gestirà automaticamente la verifica delle tue risposte e ti fornirà una correzione accurata per ciascuna domanda.

Questo progetto rappresenta una continuazione e un'evoluzione di un precedente generatore di domande sviluppato in Python mediante Jupyter Notebook, originariamente trovato nelle chat di messaggistica. *Vuoi essere citato per il progetto? Vedi le [FAQ](#FAQ)*

**Disclaimer**:

- Le domande contenute in questo generatore sono state raccolte da varie fonti nel corso degli anni, principalmente da Ariel e da altri studenti, insieme alle relative soluzioni.
- Questo generatore è stato concepito come uno strumento complementare con l'obiettivo di fornire supporto per l'allenamento con domande simili a quelle che potrebbero essere presentate durante gli esami del corso.
- Tuttavia, è fondamentale sottolineare che questo strumento non può sostituire lo studio accurato dei materiali ufficiali del corso, disponibili sul sito web ufficiale dell'Università.

## Sommario
- [Stack](#Stack)
- [Versione](#Versione)
- [Installazione](#Installazione)
- [Utilizzo](#Utilizzo)
- [Contributors](#Contributors)
- [Licenza](#Licenza)
- [FAQ](#FAQ)

## Versione

**1.2.2**

- Corretta risposta alla domanda sul free software

###### Versioni precedenti

**1.2.1**

- Corretto inizio quiz, rimossa cella duplicata

**1.2**

- Aggiunta la misurazione e visualizzazione del tempo totale impiegato per il quiz, il tempo impiegato per ciascuna domanda, il tempo medio di risposta, il tempo medio di risposta per risposte errate e risposte corrette
- Corretta la visualizzazione dei percorsi formativi

- Corrette diverse domande e risposte 
- Aggiunti i riconoscimenti nel README.md
- Corretto le versioni dello stack nel README.md

**1.1.2**
Aggiornato il file requirements.txt a causa di un refuso riguardo alla versione di Pandas

**1.1.1**
Corretta risposta riguardo all'influenza di mercato e aggiunto una domanda relativa allo stesso argomento

**1.1**
Fixato l'input del numero di domande, ora viene chiesto prima di inserire su quali argomenti si vuole testare la propria preparazione così da effettuare il controllo corretto sul numero di domande possibili in base a quante domande ci sono relative ai percorsi formativi scelti

**1.0.1**
Correzione domanda riguardo ai mercati e stato del notebook al primo avvio

**1.0**
Rilascio della prima versione di QuizGenerator

## Stack

* Python: 3.10.12
* Notebook: 7.0.3
* Pandas: 2.1.0
* Numpy: 1.25.2
* Matplotlib: 3.7.2
* IPython: 8.15.0


## Installazione

Il notebook richiede i seguenti moduli Python:
- Notebook
- Pandas 
- Numpy 
- Matplotlib

In distribuzioni come Anaconda sono già presenti, altrimenti si possono installare tramite pip:
```bash
  pip install -r requirements.txt
```

## Utilizzo

Per avviare il notebook da terminale, lanciare il comando:

```bash
  python3 -m notebook
```


**Nota**: Se si utilizza Anaconda:
1. Avviare Anaconda.
2. Lanciare Jupyter Notebook.


Per utilizzare il generatore di domande una volta che il notebook è aperto nel browser, segui attentamente questi passaggi:

1. Dopo l'apertura del notebook, verrà visualizzata una schermata localhost nel tuo browser con l'elenco dei file presenti nella cartella.

2. Clicca sul file denominato 'QuizGenerator' per accedere alla schermata di codice del generatore.

3. Per eseguire il codice, premi il tasto con le due frecce rivolte verso destra (>>) situato esattamente a destra del tasto "↻" e a sinistra della scritta "code". Importante: Non premere "RUN" in quanto questo comando eseguirebbe tutte le celle.

4. Una volta avviata l'esecuzione, sarai guidato attraverso il processo di creazione di un quiz personalizzato. Puoi personalizzare il numero di domande (il valore predefinito è 16, come nell'esame) e gli argomenti su cui desideri testare la tua preparazione (il valore predefinito include tutti gli argomenti).

5. Dopo aver risposto a tutte le domande, verrà visualizzato il risultato del tuo esame. Per ottenere la promozione, è necessario ottenere un punteggio superiore a 9/16, come richiesto in sede d'esame. Inoltre, verrà mostrata la percentuale di successo, un grafico che illustra la distribuzione delle domande per argomento e un altro grafico che indica la percentuale di risposte corrette per ciascun argomento. Dalla versione 1.2 è presente anche il tempo totale impiegato per il quiz, il tempo impiegato per ciascuna domanda, il tempo medio di risposta, il tempo medio di risposta per risposta errate e risposte corrette. Infine, avrai accesso alla lista completa delle domande, con le risposte corrette.

6. Se desideri eseguire un nuovo set di domande, puoi ripartire dal passaggio 3.

Ti auguriamo un'efficace preparazione utilizzando il generatore di domande e ti ricordiamo l'importanza di raggiungere una solida comprensione degli argomenti trattati nel corso.

## Contributors
Si ringrazia tutti e tutte coloro che stanno contribuendo al progetto:
- [AndreaaCosentino](https://github.com/AndreaaCosentino)
- [d-ber](https://github.com/d-ber)
- [Ivan Selvaggio](https://github.com/Rivan017)
- [Matteo Mangioni](https://github.com/MatMangio)
- [SarettaBalu](https://github.com/SarettaBalu)

## Licenza

[GNU GPLv3](https://choosealicense.com/licenses/gpl-3.0/)

## FAQ

#### Quali domande sono presenti?

Le domande presenti nel generatore sono tutte quelle che si possono trovare sul sul sito Ariel, in aggiunta alle quali sono state inserite quelle che condividono gli studenti sui vari gruppi di messaggistica con le relative soluzioni. Pertanto, alcune domande e risposte potrebbero essere imprecise poiche sono state formulate dagli studenti durante la fase di studio e preparzione, di conseguenza non sono state corrette dai professori del corso.

#### Se trovo un errore nelle domande lo posso correggere?

Sì assolutamente, se dovesse esserci selezionata la risposta sbagliata basta sostituire nella colonna *RispostaCorretta* il nome della colonna contenente la risposta effettivamente corretta, il cui nome puo essere uno tra: 
- *Risposta0*
- *Risposta1*
- *Risposta2*
- *Risposta3*

In seguito alla modifica si può aprire una pull request per aggiornare il dataset delle domande nel branch principale.

#### Sono sufficienti le domande del generatore per passare l'esame?

No, il generatore è pensato per essere un valido supporto allo studio dei materiali presenti sul sito ufficiale del corso. Le domande presenti nel dataset del generatore sono da intendersi come un elenco non esaustivo delle domande che possono essere richieste in sede d'esame.

#### Non ricalca un genereatore già esistente?

Questo progetto rappresenta una continuazione e un'evoluzione di un precedente generatore di domande sviluppato in Python mediante Jupyter Notebook, originariamente trovato nelle chat di messaggistica. Nel caso tu fossi il creatore o la creatrice del codice originale, contattami su Telegram (@fede02p) in modo da poter fornirti l'adeguato riconoscimento.
