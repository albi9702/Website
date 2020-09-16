---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Propensity to Churn"
summary: "A Digital Marketing Project"
authors: ["admin"]
tags: [Digital Marketing, Machine Learning, Data Science]
categories: []
date: 2020-09-14

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
links:
- name: Follow
  url: https://www.linkedin.com/in/alberto-filosa-31408/
  icon_pack: fab
  icon: linkedin

url_code: "https://github.com/albi9702/Propensity-To-Churn/blob/master/Propensity-to-Churn.Rmd"
url_pdf: "https://github.com/albi9702/Propensity-To-Churn/blob/master/Digital-Marketing-Filosa.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

# Digital Marketing

##### A Digital Marketing Project

## Sommario
In questo studio sono state analizzate le informazioni di una azienda specializzata nella vendita di prodotti. Dopo un lavoro di pre-processing e di pulizia dei dati, è stata effettuata una analisi esplorativa e tecniche di Machine Learning per identificare i clienti maggiormente affezionati e quelli che potenzialmente non acquisteranno più prodotti. Infine, è stata effettuata una analisi delle spese dei clienti.

## Obiettivi

* **RFM**: Recency, Frequency e Monetary sono delle misure di analisi di Marketing utilizzate per identificare i migliori clienti. Il modello RFM si basa su 3 principali fattori:
    + Recency: quanto tempo fa il cliente ha acquistato un prodotto;
    + Frequency: il numero totale di acquisti;
    + Monetary: Spesa totale degli acquisti.
* **MBA**: La Market Basket Analysis è una delle principali tecniche utilizzate dalle aziende per individuare dei pattern nell’acquisto dei prodotti. L’obiettivo dell’analisi è individuare la probabilità di identificare l’associazione tra i 100 prodotti più venduti.
* **Churn**: Il Churn è un modello di Marketing che applicato ad una base di clienti ed identifica se uno di essi non acquisterà più un prodotto dato un certo periodo. Esso è strettamente legato al profitto ella azienda. Inoltre, identifica le aree dove il servizio clienti è meno presente.


## Dataset
Per rispondere alle domande di analaisi si è preso in considerazione il dataset *Advise Only* dell'azienda Virtual B. Il dataset presenta le seguenti variabili:

* Fidelity:
    + Cliente;
    + Negozio;
    + Fedeltà;
    + Account Principale;
    + Data di Attivazione;
* Account:
    + Telefono;
    + Email;
    + Tipo di Account;
    + Tipo di Lavoro;
* Address:
    + CAP;
    + Provincia;
    + Regione;
* Privacy:
    + Flag Privacy;
    + Flag Marketing;
* Campaign:
    + Tipo di Campagna;
    + Consegna
    + Tipo di Evento;
* Ticket:
    + Transazione;
    + Importo;
    + Sconto;
    + Acquisto o Reso.
