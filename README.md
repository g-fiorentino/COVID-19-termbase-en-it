# COVID-19 TermBase (Inglese-Italiano)

### 1. La termbase

Il presente database terminologico inglese-italiano sul dominio COVID-19 è stato costruito al fine di favorire l'accesso dei professionisti a risorse traduttive su un tema di forte attualità e promuovere la disseminazione di contenuti tradotti di alta qualità. La termbase è disponibile nei formati:
- **XML+XDT**, utilizzabili per importare le schede terminologiche in software di gestione di terminologia quali *SDL MultiTerm Desktop* e CAT Tool come *memoQ*.
- **TXT**, per l'integrazione in CAT Tool che supportano glossari semplici (strutturati su tre colonne separate da tabulazioni) quali *OmegaT*.

La termbase consta di **195** termini in lingua inglese (cui sono associati **195** equivalenti traduttivi in lingua italiana). Poiché questo lavoro terminologico vuole essere un aiuto concreto per tutti i traduttori che si trovino, in questo momento di difficoltà, ad avere a che fare con testi che ruotano attorno all’argomento COVID-19, è stato ritenuto necessario che la termbase di progetto coprisse, nei limiti delle risorse e dei tempi disponibili, una varietà il più possibile completa e rappresentativa dei campi del sapere e dei tipi testuali toccati dal dominio COVID-19. A questo fine, la termbase include terminologia legata non solo al discorso scientifico e tecnico di ambito medico, ma anche alla comunicazione divulgativa nonché di carattere legislativo ed emergenziale. 

Il database terminologico è stato costruito nell'ambito di un più ampio lavoro di tesi. L'accesso al file di tesi che descrive il progetto può essere concesso previa richiesta. Per citare la termbase all'interno di un lavoro di ricerca, si prega di utilizzare:
> Fiorentino, Giancarlo. 2021. «Terminologia basata su corpora ed estrazione terminologica automatica: costruzione di una termbase inglese-italiano nel dominio COVID-19». Università degli Studi di Bologna, Bologna.

### 2. Metodologie di costruzione della termbase e risorse testuali utilizzate

Nel processo di estrazione terminologica ai fini della costituzione della termbase sono stati utilizzati approcci metodologici di diversa natura. Il primo approccio si è basato sull’estrazione terminologica automatica effettuata mediante *Almaligner*, software sperimentale attualmente in corso di sviluppo presso il Dipartimento di Traduzione e Interpretazione dell’Università di Bologna (https://docs.sslmit.unibo.it/doku.php?id=almaligner:start). Il pool di dati linguistici su cui si è concentrata questa prima porzione del lavoro è composto da memorie di traduzione prodotte a partire da una molteplicità di fonti, contenenti frammenti di testi source in lingua inglese allineati a equivalenti tradotti in italiano. Le coppie di testi tradotti da cui sono state tratte le memorie di traduzione sono state reperite online o consultando elenchi di documentazione disponibile relativa al dominio quali la pagina principale del progetto TICO-19 (https://tico-19.github.io/). Il set di dati finale consta di **5** memorie, per un totale di **1874** unità di traduzione. Ulteriori caratteristiche, quali il numero di unità di ciascuna memoria e di type e token dei corpora testuali corrispondenti, sono riassunte nella seguente tabella.

| Set di dati | Unità di traduzione | Type | Token | Fonte |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| Coronasurveys | 22 | 140 | 256 | https://coronasurveys.org/ |
| COVID-19 Service User Advice - Doctors of the World | 84 | 360 | 1235 | https://www.doctorsoftheworld.org.uk/coronavirus-information/ |
| Evidenceaid | 823 | 4382 | 39364 | https://evidenceaid.org/evidence/coronavirus-covid-19/ |
| COVID19 Myth Busters in World Languages | 29 | 194 | 445 | https://covid-no-mb.org |
| Zhejiang Handbook of COVID-19 Prevention and Treatment | 916 | 2716 | 15151 | https://gmcc.alibabadoctor.com/prevention-manual?content_id=0 |
| **Totale** | 1874 | 7792 | 56451 |  |

Per rifinire l’output di Almaligner e verificare la correttezza e appropriatezza sia dei termini estratti che delle traduzioni assegnate automaticamente a ciascun termine, alla fase di estrazione è seguita una fase di validazione, un processo di analisi manuale di corpora di testi pertinenti al dominio d’interesse elaborati mediante il concordancer **Antconc** (https://www.laurenceanthony.net/software.html). Successivamente, per ampliare ulteriormente l’orizzonte del database terminologico ed espandere il ventaglio di termini inclusi nella termbase finale, il lavoro terminologico è proseguito con una fase di estrazione terminologica manuale effettuata sempre tramite Antconc. I corpora utilizzati in questa fase sono di tipo monolingue comparabile e sono stati creati ad hoc per il progetto.

I due corpora comparabili in inglese e italiano sono composti da quattro sub-corpora, due formati da articoli di giornale, due da articoli scientifici. Gli articoli che compongono i due sub-corpora tratti da quotidiani sono stati selezionati a seguito di ricerche sul motore di ricerca *Google*, restringendo le query ai siti web di 5 quotidiani di lingua italiana (*La Stampa, Corriere della Sera, Il Fatto Quotidiano, La Repubblica, Il Messaggero*) e 5 quotidiani di lingua inglese (*The New York Times, The Washington Post, The Guardian, The Independent, USA Today*) e includendo parole chiave come “covid” e rimandi a contesti geografici come “italia” o “us”. Gli articoli dei sub-corpora giornalistici sono stati scelti in modo da essere il più possibile rappresentativi del dominio COVID-19. A questo scopo, sono stati selezionati pezzi che parlassero di singoli medicinali in sviluppo o già esistenti, notizie sull’andamento dell’epidemia o delle campagne vaccinali, materiale a carattere divulgativo (ad esempio, consigli di medicina di esperti del settore, approfondimenti sul funzionamento dei vaccini o su nuove ricerche scientifiche) e guide sui comportamenti da tenere in vari setting nel corso della pandemia (in palestra, al cinema). Riassumendo, il sub-corpus di articoli di giornale di lingua italiana, composto da **50** articoli, consta di **50.545** parole ed è stato tratto dalla versione web di cinque quotidiani pubblicati su scala nazionale. Il sub-corpus di articoli di giornale di lingua inglese comprende le varietà britannica e americana e include **50.242** parole, con **50** testi. Informazioni più dettagliate sono disponibili nelle seguenti tabelle.

| Sub-corpus quotidiani di lingua italiana | Type | Token | Testi|
| ------------- | ------------- | ------------- | ------------- |
|La Stampa | 1877 | 5783 | 10|
|Corriere della Sera | 2778 | 12250 | 10|
|Il Fatto Quotidiano | 3618 | 17922 | 10|
|La Repubblica | 3012 | 11134 | 10|
|Il Messaggero | 1207 | 3456 | 10|
|Totale | 7271 | 50561 | 50|

|Sub-corpus quotidiani di lingua inglese | Type | Token | Testi |
| ------------- | ------------- | ------------- | ------------- 
|The New York Times | 2669 | 13415 | 10 |
|The Washington Post | 2442 | 12009 | 10 |
|The Guardian | 1873 | 8380 | 10 |
|The Independent | 1790 | 7659 | 10 |
|USA Today | 2163 | 8779 | 10 |
|Totale | 5698 | 50242 | 50 |

Gli articoli dei sub-corpora scientifici sono stati individuati attraverso motori di ricerca di letteratura biomedica (*PubMed*) e accademica in generale (*Google Scholar*), limitando le query ai risultati in lingua italiana o inglese e utilizzando la keyword “covid-19”. Gli articoli scientifici selezionati includono studi sull’interazione tra COVID-19 e altre patologie (ad esempio, studi su diabete mellito e COVID-19 o salute mentale e COVID-19), brevi compendi di letteratura scientifica, ricerche sui possibili risvolti cardiovascolari della malattia e analisi sul calcolo statistico degli indici Rt o R0. Il sub-corpus di articoli scientifici di lingua italiana comprende **11** articoli e **34.053** parole, il corrispettivo in lingua inglese conta **8** articoli e **34.992** parole. Il computo dei type, delle parole totali e del numero di testi dei due corpora è riportato nella seguente tabella.

|Sub-corpus articoli scientifici | Type | Token | Testi |
| ------------- | ------------- | ------------- | ------------- 
|Italiano | 4813 | 34053 | 11 |
|English | 4388 | 34992 | 8 |
|Totale | 9.201 | 69045 | 19 |

In totale, i corpora comparabili utilizzati per la validazione e l’estrazione terminologica manuale contano **84.614** e **85.234** parole. La seguente tabella fornisce una panoramica finale della loro composizione. La cartella /corpora contiene un file XML con i riferimenti puntuali di ciascuno dei testi utilizzati all'interno del progetto.

|Corpus | Type | Token | Testi |
| ------------- | ------------- | ------------- | ------------- 
|Italiano | 9529 | 84614 | 61 |
|Inglese | 7836 | 85234 | 58 |

### 3. Struttura della termbase

La termbase di progetto è bilingue (inglese-italiano). Ogni voce contiene un minimo di due termini, uno per lingua. All’interno delle voci, oltre al termine principale, forma più frequentemente attestata nei corpora presi in esame, sono stati inseriti eventuali sinonimi o varianti ortografiche. La singola scheda terminologica si articola in un massimo di 8 campi, elencati di seguito:

- **“Tipologia di estrazione”** : indica la metodologia di estrazione utilizzata.
- **“Indicativo grammaticale”** : fornisce una classificazione in base alle parti del
discorso.
- **“Definizione”** : Viene estratta dai corpora utilizzati per l’analisi. Più che come descrizione di un singolo termine, la definizione è intesa come rappresentazione testuale di un concetto.
- **“Fonte definizione”** (e **“Fonte contesto”**): indicano il collegamento ipertestuale con cui reperire il materiale originale da cui l’informazione è stata tratta.
- **“Contesto”** : è un esempio in contesto estratto dai corpora di utilizzo del termine. Dove possibile, include esempi di collocazioni tipiche.
- **“Registro”** : indica se un termine è attestato in un dato registro discorsivo, determinato in base al tipo di testi da cui viene estratto.
- **“Note”** : Eventuali collocazioni, fraseologismi o differenze di utilizzo delle forme sinonimiche rispetto al termine principale.

La Figura 1 contiene una gerarchia orizzontale che chiarifica la struttura della termbase:

![struttura di una voce di termbase](https://i.ibb.co/bvjxMrB/struttura-termbase.png)

**Figura 1**: Struttura di una voce di termbase.

All'interno della termbase sono presenti due tipi di schede terminologiche, le **schede complete** e le **schede semplici**. Le schede complete sono riservate a una porzione di unità terminologiche considerate prioritarie perché, ad esempio, sono associate a concetti centrali all'interno del dominio, come l'acronimo "COVID-19", o perché si riferiscono a concetti il cui significato potrebbe risultare oscuro all'utente e dunque beneficerebbero di ulteriori chiarificazioni, come il termine semplice "corticosteroids". All'interno di queste schede, 5 degli 8 campi disponibili sono stati considerati obbligatori: tutti i termini (oltre ad almeno un equivalente traduttivo) contengono informazioni relative a Tipologia di estrazione, Indicativo grammaticale, Contesto, Fonte Contesto e Registro. Inoltre, ciascun termine principale è accompagnato da una Definizione (e dalla rispettiva Fonte). Le schede semplici, invece, contengono tutte le unità terminologiche rimanenti. Queste schede si limitano a indicare i termini in inglese, eventuali sinonimi, gli equivalenti traduttivi in italiano e la Tipologia di estrazione. Nello specifico, sono state costruite **60** schede complete, contenenti 82 termini, e 105 schede semplici, contenenti 113 termini. I dati appena illustrati sono riassunti all'interno della tabella seguente.

| Tipologia di estrazione  | Schede complete  | Schede semplici |
| ------------- | ------------- | ------------- |
| Automatica  | 10  | 46  |
| Manuale  | 72  | 67  |
| **Totale**  | 82  | 113  |
