# Scraping_fondamenta-_e_applicazione
# 🐍 Python API Scraping Tutorial: Football Data

Questo progetto è un notebook introduttivo che spiega passo dopo passo come effettuare **web scraping tramite API** utilizzando Python.
Il tutorial si concentra sull'interazione con servizi RESTful, utilizzando come caso studio reale l'API di dati calcistici **API-Sports (Football API)**.

## 📋 Contenuti del Notebook

Il notebook `Scraping spiegato.ipynb` copre i seguenti concetti fondamentali:

* **Configurazione dell'ambiente:** Importazione delle librerie essenziali (`requests`, `json`).
* **Autenticazione API:** Come impostare gli **headers** per passare la chiave di autenticazione (`x-apisports-key`) in modo sicuro.
* **Richieste GET:** Esecuzione di chiamate a diversi endpoint (es. `/leagues`, `/status`).
* **Filtraggio Dati:** Utilizzo dei dizionari `params` per filtrare le richieste (es. per nazione `"code": "IT"` o per ID lega `"id": 135`).
* **Parsing JSON:** Conversione della risposta dell'API in dizionari Python e formattazione leggibile tramite `json.dumps`.
* **Analisi della Risposta:** Come navigare nella struttura del dizionario (es. accedere alla chiave `['response']`) per estrarre i dati desiderati.

## 🛠️ Prerequisiti

Per eseguire il codice è necessario avere installato Python e le seguenti librerie:

```bash
pip install requests
