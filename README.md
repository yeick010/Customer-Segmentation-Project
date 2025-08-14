# Customer-Segmentation-Project
Analisi di clustering K-Means per segmentare i clienti di una carta di credito in base al loro comportamento di spesa.
# Segmentazione dei Clienti con Clustering K-Means

## Descrizione del Progetto
Questo progetto analizza i dati di utilizzo delle carte di credito per identificare segmenti di clienti con comportamenti di spesa simili. Utilizzando l'algoritmo di clustering non supervisionato K-Means, l'obiettivo è fornire alla banca intuizioni utili per creare campagne di marketing personalizzate.

---

## Dataset
Il dataset utilizzato è disponibile pubblicamente su Kaggle e contiene informazioni anonime su circa 9000 clienti e il loro comportamento negli ultimi 6 mesi.
[Link al Dataset su Kaggle](https://www.kaggle.com/datasets/arjunbhasin2013/ccdata)

---

## Processo di Analisi
1.  **Esplorazione e Pulizia Dati (Data Cleaning):** Analisi iniziale del dataset, gestione dei valori mancanti e rimozione delle colonne non pertinenti.
2.  **Preparazione Dati (Preprocessing):** Scaling delle feature utilizzando `StandardScaler` per standardizzare le variabili e renderle confrontabili.
3.  **Modellazione (Clustering):** Applicazione del "Metodo del Gomito" per determinare il numero ottimale di cluster. Addestramento del modello K-Means finale con k=4.
4.  **Analisi dei Segmenti:** Interpretazione delle caratteristiche di ogni cluster per definire delle "personas" di clienti (es. "VIP", "Prelevatori di Contante", etc.).

---

## Risultati
L'analisi ha identificato **4 segmenti di clienti** ben distinti, ognuno con specifiche abitudini di spesa e di utilizzo della carta. Questi profili permettono di indirizzare strategie mirate, come programmi fedeltà per i clienti "VIP" o piani di rientro per quelli ad alto indebitamento.

---

## Tecnologie Utilizzate
* **Python 3**
* **Pandas & NumPy:** Per la manipolazione e l'analisi dei dati.
* **Matplotlib & Seaborn:** Per la visualizzazione dei dati.
* **Scikit-learn:** Per l'implementazione del K-Means e il preprocessing.
---
➡️ **[Esplora i dettagli del progetto](https://github.com/yeick010/Customer-Segmentation-Project/blob/main/Segmentazione%20dei%20Clienti%20di%20una%20Carta%20di%20Credito.ipynb))**
