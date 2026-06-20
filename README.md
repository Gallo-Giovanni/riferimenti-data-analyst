# 📚 riferimenti-data-analyst

Raccolta di cheatsheet e strumenti interattivi creati durante il mio percorso di studio verso il ruolo di **Data Analyst / Data Scientist**.

I file sono stati realizzati su mie indicazioni con il supporto dell'AI, con l'obiettivo di avere un riferimento rapido, chiaro e pratico alle funzioni e ai concetti più usati — senza dover ogni volta cercare nella documentazione ufficiale.

---

## 📂 Contenuto della repository

| File | Argomento | Cosa trovi |
|------|-----------|------------|
| `numpy_pandas_essenziali.pdf` | **NumPy & Pandas** | Le funzioni e i metodi più usati per l'analisi dati: creazione array, operazioni statistiche, caricamento e pulizia dati, join, groupby, pivot e molto altro |
| `strutture_dati_python_essenziali.pdf` | **Strutture dati Python** | Panoramica e metodi principali di list, tuple, dict, str, set e array — con sintassi, esempi e note su quando usare cosa |
| `riferimento_sql_completo.pdf` | **SQL** | Tutte le clausole principali: SELECT, JOIN, WHERE, GROUP BY, HAVING, window functions, CTE, DML/DDL — con una query master completa alla fine |
| `sql-execution-explainer.html` | **SQL interattivo** | Tool a 4 pannelli con database SQLite eseguibile nel browser: reference per clausola, editor query, ordine di esecuzione spiegato passo-passo, risultato reale della query. **[→ Apri live](https://sql-explainer.netlify.app/)** |

---

## 🎯 A chi serve

A chiunque stia studiando **data analysis o data science** e voglia un riferimento pratico da consultare velocemente durante esercizi, progetti o ripasso — in particolare per chi sta imparando SQL e vuole capire **perché** una query si comporta in un certo modo, non solo la sintassi.

---

## 🛠️ Come sono stati creati

I cheatsheet e gli strumenti sono stati progettati su mie indicazioni personali durante il percorso di studio, con l'aiuto dell'AI come strumento di supporto alla produzione. La struttura, i contenuti e le priorità riflettono le mie esigenze reali di studio — non documentazione generica copiata, ma una selezione ragionata delle cose che uso davvero, testata direttamente sui dati per garantire che ogni esempio funzioni davvero.

---

## 🧠 SQL Execution Explainer — il tool

Un'applicazione web standalone (nessuna installazione richiesta) pensata per capire **davvero** come funziona una query SQL, non solo come si scrive.

### Cosa fa

- **Esegue query SQL reali** nel browser tramite [sql.js](https://github.com/sql-js/sql.js) (SQLite compilato in WebAssembly) su un database di esempio con 4 tabelle collegate (`clienti`, `ordini`, `prodotti`, `categorie`) e dati realistici
- **Spezza la query per clausola** nell'ordine in cui è scritta (`WITH`, `SELECT`, `FROM`, `WHERE`...) mostrando esattamente quale porzione di testo appartiene a quale clausola — gestisce correttamente CTE annidate e subquery
- **Mostra l'ordine reale di esecuzione** del motore SQL (FROM → WHERE → GROUP BY → HAVING → SELECT → ORDER BY → LIMIT), diverso da come la query viene scritta, con spiegazione per ogni passaggio e avvisi sugli errori più comuni
- **Visualizza il risultato** della query come tabella vera, con conteggio righe, tempo di esecuzione e gestione degli errori SQL
- **Reference completo per ogni clausola**, con decine di funzioni spiegate (aggregate, stringhe, date, window function, JOIN, DML/DDL) ciascuna con un esempio eseguibile direttamente con un click
- **Modalità "Guida al Ragionamento"** — una vista dedicata che aiuta a tradurre una domanda in linguaggio naturale ("quanti...", "il più alto...", "per ogni gruppo...") nella clausola SQL corretta da usare, più i pattern più comuni (window function, JOIN, NULL, conversioni di tipo, ordine di esecuzione)
- **Esempi pratici pronti** — duplicati (due varianti: GROUP BY ed EXISTS), top N per gruppo, totali cumulativi, clienti senza ordini, confronti anno su anno, percentuali sul totale, pivot manuali, filtri su rank

### Come usarlo

1. Apri [sql-explainer.netlify.app](https://sql-explainer.netlify.app/) (oppure scarica `sql-execution-explainer.html` e aprilo con un browser)
2. Scrivi o incolla una query SQL nel pannello centrale
3. Premi **Analizza**
4. Esplora come la query viene letta, eseguita e quale risultato produce

---

## 📌 Stack di riferimento

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)](#)
[![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)](https://www.sqlite.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)](https://numpy.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](#)
