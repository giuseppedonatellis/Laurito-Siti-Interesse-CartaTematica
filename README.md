# Comune di Laurito – Carta dei siti di interesse geologico, naturalistico, archeologico e turistico

## Descrizione del progetto  
Questo progetto ha come obiettivo la creazione di una carta tematica dei siti di interesse geologico, naturalistico, archeologico e turistico presenti nel Comune di Laurito (SA). I dati sono stati acquisiti tramite fonti regionali (servizio WMS della Regione Campania) e integrati con una base cartografica georiferita. Ogni sito è stato categorizzato per tipologia e etichettato con il proprio nome, per offrire una mappa chiara e leggibile.

## Obiettivo dell’esercitazione  
- Creare una mappa tematica dei siti di interesse (geologico, naturalistico, archeologico, turistico).  
- Riportare i siti sulla base cartografica e categorizzarli.  
- Associare a ciascun sito un’etichetta contenente il nome.  
- Esportare una mappa in formato A4 (JPG, TIFF o PDF) completa di:  
  - Freccia del nord  
  - Barra di scala  
  - Legenda  
  - Coordinate  

## File principali  

### Layer vettoriali
- Siti di interesse del comune di Laurito.shp  
  → Shapefile dei siti tematici con attributi relativi a nome e categoria.

- Laurito.shp  
  → Confine comunale utilizzato come contesto spaziale.

### Layer WMS  
- Servizio cartografico WMS:  
  https://sit2.regione.campania.it/content/servizi-wms  
  → Base informativa regionale per arricchimento e verifica.

### Progetto QGIS  
- Giuseppe Donatellis_step4.qgz  
  → Progetto completo con:
  - Layer di siti tematici con simbologia distinta per categoria.
  - Etichette visibili per ogni punto.
  - Layout di stampa con tutti gli elementi cartografici.

### Output finale  
- Mappa A4 esportata in formato .jpg, .tiff o .pdf con:
  - Simboli differenziati per tipologia di sito
  - Etichette leggibili
  - Coordinate, scala, freccia nord, legenda

## Coordinate di riferimento (CRS)  
- EPSG:32633 – WGS 84 / UTM zona 33N

## Software utilizzato  
- QGIS 3.30.x o superiore  
- Servizio WMS Regione Campania  
- Etichettatura automatica e simbologia categorizzata

## Flusso operativo  

1. Importazione dei dati shapefile o tramite servizio WMS.  
2. Categorizzazione dei siti per tipologia (archeologico, turistico, ecc.).  
3. Applicazione etichette ai punti tramite il campo nome.  
4. Impostazione della simbologia e del layout cartografico.  
5. Esportazione in A4 con legenda, coordinate, freccia nord e barra di scala.

## Risultati e applicazioni  
- Carta di sintesi dei luoghi d’interesse del Comune di Laurito.  
- Utile per progetti di valorizzazione turistica, culturale e ambientale.  
- Supporto per piani urbanistici o percorsi tematici.

## Autore  
Giuseppe Donatellis  
Corso GIS e Cartografia Geotematica – Università degli Studi di Napoli Federico II

## Suggerimenti per utilizzo futuro  
- Integrare con dati su accessibilità, percorsi, servizi o itinerari.  
- Collegare i punti mappa a schede descrittive o contenuti WebGIS.

## Accesso ai dati
https://drive.google.com/drive/folders/1JPONY9p05AFiEmI8PQz0fy_AOHeQIgVs?usp=drive_link

## Accesso ai dati 
https://drive.google.com/drive/folders/1JPONY9p05AFiEmI8PQz0fy_AOHeQIgVs?usp=drive_link
