# Analisi della produttività nella manifattura: un confronto tra modelli predittivi 🏭

Questo progetto di Machine Learning mira a predire l'efficienza produttiva di una fabbrica tessile utilizzando un dataset reale: il *Garments Worker Productivity Dataset*.

## 👥 Autori
* Lorenzo Scetto
* Annabella Imperatore

## 🎯 Obiettivo del Progetto
L'obiettivo principale è sviluppare e confrontare diversi modelli predittivi per stimare la produttività effettiva (`actual_productivity`) dei team di lavoro, partendo da variabili come il tempo standard assegnato, gli straordinari, gli incentivi finanziari e il numero di lavoratori.

## ⚙️ Modelli Utilizzati
Sono stati applicati e confrontati i seguenti modelli di regressione supervisionata:
* **Random Forest**
* **XGBoost**
* **Support Vector Regression (SVR)**

Tutti i modelli sono stati valutati utilizzando tecniche di validazione incrociata (Cross-Validation) e metriche di valutazione standard.

## 📊 Analisi Esplorativa dei Dati (EDA)
Nel notebook è presente un'approfondita analisi esplorativa che analizza l'impatto di diverse variabili sulla produttività, tra cui:
* `targeted_productivity`: Produttività attesa
* `smv`: Standard Minute Value
* `over_time`: Minuti di straordinario
* `incentive`: Incentivo finanziario
* `no_of_workers`: Numero di lavoratori per team

## 🚀 Come visualizzare il codice
Puoi esplorare tutto il codice e l'analisi cliccando sul file `.ipynb` presente in questo repository. Grazie all'integrazione con Google Colab, puoi anche eseguire il codice direttamente nel tuo browser cliccando sull'apposito badge "Open in Colab" all'interno del file!
[👉 Clicca qui per leggere il report completo in PDF](Report_Analisi_Produttivita.pdf)
