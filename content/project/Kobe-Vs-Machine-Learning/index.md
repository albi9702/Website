---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Kobe vs Machine Learning"
summary: "A Machine Learning Project"
authors: [admin]
tags: [Data Science, Machine Learning, Kobe Bryant, Basketball]
categories: []
date: 2020-02-14

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

url_code: "https://github.com/albi9702/Kobe-Vs-Machine-Learning/blob/master/Workflow_Team_48.knwf"
url_pdf: "https://github.com/albi9702/Kobe-Vs-Machine-Learning/blob/master/Report_Team_48.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

##### A Machine Learning Project

## Sommario

In questo studio sono stati analizzati i tiri tentati da Kobe Bryant nel
corso della sua carriera, al fine di costruire un modello in grado di
prevedere se il tiro entri o meno nel canestro. In particolare,
attraverso l’utilizzo di tecniche di Machine Learning, sono stati
applicati e confrontati diversi modelli di predizione binaria e tecniche
di valutazione della Variable Importance. I risultati sono stati
proposti secondo un’ottica di utilizzo reale dei dati nel corso di una
partita, al fine di limitare il rendimento del giocatore avversario.

## Obiettivi

L’idea di partenza dell’analisi è stata quella di mettersi nei panni di
un ipotetico allenatore avversario per cercare di capire come affrontare
Kobe Bryant, analizzando i suoi punti di forza e quelli di debolezza nel
tirare a canestro. Le domande di ricerca in particolare sono state:

1.  Da quale posizione è più favorevole far tirare Kobe Bryant per
    evitare di subire un canestro?
2.  L’efficacia nel tiro dipende solo dalla distanza o dipende anche da
    altre circostanze?

## Dataset

Per rispondere alle domande dell’analisi è stato preso in considerazione
il dataset “Kobe Bryant Shot Selection”, relativo ad una competition del
sito di
[Kaggle](https://www.kaggle.com/c/kobe-bryant-shot-selection/overview) .
Il dataset è composto da 30698 osservazioni e 25 variabili, che vengono
spiegate di seguito:

1.  *combined\_shot\_type*: tipologie di tiro generiche (6 livelli);
2.  *action\_type*: tipologie di tiro specifiche (57 livelli);
3.  *game\_event\_id*: identificatore di ogni singola azione della
    partita;
4.  *lat*: latitudine dello stadio;
5.  *lon*: longitudine dello stadio;
6.  *loc\_x*: coordinata sull’asse x da cui viene tentato il tiro (-250
    indica la linea laterale destra, 250 indica la linea laterale
    sinistra);
7.  *loc\_y*: coordinata sull’asse y da cui viene tentato il tiro (-40
    indica la linea di fondo dietro al canestro verso cui viene
    effettuato il tiro, 900 la linea di fondo opposta);
8.  *minutes\_remaining*: minuti rimanenti in un periodo;
9.  *period*: periodo di gioco (4 periodi più eventuali supplementari);
10. *playoff*: variabile binaria, indica se la partita si giochi nei
    Playoff o in Regular Season;
11. *season*: stagione in corso;
12. *seconds\_remaining*: secondi rimanenti nel periodo;
13. *shot\_distance*: distanza da cui è stato tentato il tiro (in
    piedi);
14. *shot\_type*: variabile binaria, indica se il tiro è da 2 o da 3
    punti;
15. *shot\_zone\_basic*: zona del campo da cui viene tentato il tiro (7
    livelli);
16. *team\_id*: identificativo della squadra (costante “LA”);
17. *team\_name*: nome della squadra (costante “Los Angeles Lakers”);
18. *game\_date*: data in cui si è giocata la partita;
19. *matchup*: squadre che si affrontano;
20. *opponent*: nome della squadra avversaria;
21. *game\_id*: identificativo della partita;
22. *shot\_id*: identificativo del tiro effettuato;
23. *shot\_made\_flag*: variabile binaria, indica se il tiro sia stato
    messo a segno o no;
24. *shot\_zone\_area*: area del campo da cui viene tentato il tiro (6
    livelli);
25. *shot\_zone\_range*: range di distanza da cui viene tentato il tiro
    (5 livelli).

## Team 48

- Gabriele Carrara:
    - Triennale: Statistica e Gestione delle Informazioni | Università
      degli Studi di Milano-Bicocca;
    - Magistrale: Data Science | Università degli Studi di
      Milano-Bicocca;

<center>
  <a href = "https://www.linkedin.com/in/gabriele-carrara-968310198/"><i class="fab fa-linkedin"></i></a>
</center>

- Davide Garavaldi:
    - Triennale: Statistica e Gestione delle Informazioni | Università
      degli Studi di Milano-Bicocca;
    - Magistrale: Data Science | Università degli Studi di
      Milano-Bicocca;

<center>
  <a href = "https://www.linkedin.com/in/davide-garavaldi-ba9487195/"><i class="fab fa-linkedin"></i></a>
</center>

- Simone Tufano:
    - Triennale: Statistica e Gestione delle Informazioni | Università
      degli Studi di Milano-Bicocca;
    - Magistrale: Data Science | Università degli Studi di
      Milano-Bicocca;

<center>
  <a href = "https://www.linkedin.com/in/simone-tufano-957763162/"><i class="fab fa-linkedin"></i></a>
</center>
