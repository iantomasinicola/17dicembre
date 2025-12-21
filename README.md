# Implementazione di un algoritmo di previsione per serie storiche

## Scomposizione additiva sviluppata da zero in Python

Questo project work presenta la progettazione e l’implementazione **da zero in Python** di un algoritmo di **scomposizione additiva delle serie storiche**, finalizzato all’analisi e alla previsione dell’andamento temporale dei dati.

L’approccio adottato prevede la separazione esplicita della serie nelle sue componenti fondamentali:
- **Trend**
- **Stagionalità**
- **Componente residua**

A partire da questa scomposizione, viene costruito un modello di previsione in grado di estendere la dinamica osservata oltre l’orizzonte temporale disponibile, mantenendo interpretabilità e controllo completo sul processo algoritmico.

L’obiettivo del lavoro è duplice:
- comprendere in modo approfondito i meccanismi alla base del forecasting delle serie storiche;
- sviluppare una soluzione trasparente e riproducibile, senza ricorrere a librerie di alto livello già pronte all’uso.

## Contenuti del repository

- `data input/`
  - Dataset di esempio in formato `.csv`
    File scaricato da https://support.microsoft.com/it-it/office/creare-una-previsione-in-excel-per-windows-22c500da-6da7-45e5-bfdc-60a7062329fd


- `Project_work.ipynb`
  - Notebook con l'implementazione *da zero* della decomposizione additiva delle serie storiche.
