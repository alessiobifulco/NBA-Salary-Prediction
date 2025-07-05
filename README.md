# 🏀 Predizione e Analisi degli Stipendi NBA


**Corso:** Progetto Corso di Applicazioni Data Intensive

---

## 🎯 Concetto di Base
Questo progetto consiste in un'analisi "data-intensive" volta a comprendere le dinamiche economiche del mercato NBA. L'obiettivo è sviluppare un modello di machine learning in grado di **predire lo stipendio medio annuale** di un giocatore basandosi sulle sue performance statistiche.

- **Contesto:** Il mercato dei giocatori NBA, dove le performance si traducono in valore economico.
- **Obiettivo Principale:** Creare una "formula" basata sui dati per stimare il "giusto" valore di un giocatore.
- **Applicazione Finale:** Utilizzare il modello per analizzare giocatori in stagioni recenti, valutando l'impatto delle variazioni di performance sul loro valore predetto.

## 🏛️ Il Flusso di Lavoro
L'analisi è stata strutturata seguendo un flusso di lavoro standard nel mondo della Data Science, suddiviso in fasi logiche e sequenziali.

- **1. Pulizia e Feature Engineering:** La fase iniziale, in cui i dati grezzi vengono trasformati in un dataset pulito, consistente e arricchito con nuove feature più significative (es. statistiche "per partita", durata del contratto).
- **2. Analisi Esplorativa (EDA):** È la fase investigativa, in cui tramite visualizzazioni (heatmap, scatter plot) e statistiche si scoprono i pattern nascosti, le relazioni tra le variabili e si identificano i fattori più influenti.
- **3. Modellazione e Valutazione:** La fase centrale, in cui vengono addestrati e confrontati diversi modelli di regressione per trovare quello più accurato.
- **4. Ottimizzazione e Applicazione:** La fase finale, in cui il modello migliore viene ottimizzato e poi applicato a dati nuovi per generare insight pratici.

## 🧩 Tecniche di Analisi e Modellazione Utilizzate
Per la realizzazione del progetto sono state utilizzate diverse tecniche statistiche e di machine learning.

- **Regressione Lineare (Ridge & Lasso):** Modelli utilizzati per la loro interpretabilità. Creano una relazione lineare tra le statistiche e lo stipendio, e i loro coefficienti rappresentano la "formula" più semplice per capire l'impatto di ogni statistica.
- **Random Forest:** Un modello ad albero non-lineare e molto potente, utilizzato per ottenere una maggiore accuratezza predittiva catturando relazioni più complesse nei dati. La sua "formula" è data dall'importanza delle feature.
- **Cross-Validation:** Una tecnica robusta per la valutazione dei modelli. Invece di una singola divisione dei dati, il processo di addestramento e test viene ripetuto più volte per ottenere una stima più stabile e affidabile della performance reale del modello.
- **Grid Search:** Una tecnica per l'ottimizzazione automatica degli iperparametri di un modello. Testa sistematicamente diverse combinazioni di impostazioni per trovare quella che massimizza le performance.

## 🛠️ Tecnologie e Librerie Chiave
- **Linguaggio: Python 3**
- **Pandas**
  - La libreria fondamentale per la manipolazione e l'analisi dei dati. Utilizzata per caricare i file, pulire le informazioni e creare il nostro DataFrame finale.
- **Matplotlib & Seaborn**
  - Le librerie principali per la visualizzazione dei dati. Utilizzate per creare tutti i grafici del progetto, come heatmap, scatter plot e grafici a barre.
- **Scikit-learn**
  - La libreria di machine learning più importante in Python. Utilizzata per ogni fase della modellazione: dalla preparazione dei dati (`StandardScaler`) alla creazione dei modelli (`Ridge`, `RandomForestRegressor`), fino alla loro valutazione e ottimizzazione (`cross_validate`, `GridSearchCV`).

## 👤 Contatti
- Alessio Bifulco: `[alessio.bifulco@studio.unibo.it]`
