---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Does the Weather Actually Affect Your Mood?"
summary: "A Data Management and Visualization Project"
authors: [admin]
tags: [Data Management, Data Visualization, Data Science]
categories: []
date: 2020-07-15

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/albi9702/Does-the-weather-actually-affect-your-mood/blob/master/Script-DM.pdf"
url_pdf: "https://github.com/albi9702/Does-the-weather-actually-affect-your-mood/blob/master/Report_Carrara_Filosa.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

##### A Data Management and Visualization Project

## Sommario
Il fine dello studio è la comprensione della relazione presente tra il clima e l’umore delle persone. Per scoprirlo si è proceduto all’analisi della polarità di un anno di tweets (2019), mettendo questi in rapporto con le temperature locali del giorno. Sono state considerate le città di Milano, Roma, Napoli e Palermo e l’area ad essa circostante in un raggio di 100 km. Sono stati estratti i tweet contenenti almeno una delle
seguenti parole: freddo, sole, nuvole, pioggia, neve, temperatura e caldo.

## Obiettivi

* Statistiche Descrittive del tempo atmosferico;
* Controllo Qualità Dati;
* Sentiment Analysis con le API di Meaning Cloud;
* Simulazione della Velocity con Producer e Consumer.
* Infografiche tramite Tableau.

## Dataset

### Dati Meteo
La raccolta dei dati meteo è stata effettuata tramite procedure di scraping dal sito Il Meteo. Sono state estratte le temperature minime, medie e massime giornaliere delle città di Milano, Roma, Napoli e Palermo per tutto il 2019. Sul sito però non erano presenti i dati da Agosto a Ottobre per la città di Milano. Per risolvere questo
problema, sono stati recupati dal sito Rp5 le temperature mancanti ed aggiunte al dataset di partenza. Anche in questo caso, vi erano dei valori mancanti in alcuni giorni di ottobre. Per colmare questa ultima lacuna, sono stati raccolti i dati dal sito Tu Tiempo.

### Tweets
Per raccolta dei tweets nell’anno 2019 non è stato possibile utilizzzare le API di Twitter in quanto presentavano delle restrizioni in termini di tempo e quantità. Si è perciò optato per l’utilizzo del pacchetto Python GetOldTweets3 direttamente dalla linea di comando che permette di creare una tabella contenente i tweets per il periodo ed il luogo desiderato.

## Team

- Gabriele Carrara:
    - Triennale: Statistica e Gestione delle Informazioni | Università degli Studi di Milano-Bicocca;
    - Magistrale: Data Science | Università degli Studi di Milano-Bicocca;

<center>
  <a href = "https://www.linkedin.com/in/gabriele-carrara-968310198/"><i class="fab fa-linkedin"></i></a>
</center>
