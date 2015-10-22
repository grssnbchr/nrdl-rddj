---
title       : Reproduzierbarkeit im Datenjournalismus
subtitle    : Beispiele mit R
author      : Timo Grossenbacher
job         : Datenjournalist @srfdata
framework   : revealjs        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : default      # 
revealjs:
  theme: default
  transition: none
  center: "true"
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---


### nr-Datenlabor
## Reproduzierbarkeit im #DDJ

### Warum und wie? 

Timo Grossenbacher, SRF Data

[@grssnbchr](http://twitter.com/grssnbchr)

[@srfdata](http://twitter.com/srfdata)

Präsentation vefügbar unter [grssnbchr.github.io/nrdl-rddj](http://grssnbchr.github.io/nrdl-rddj)

---

### Über mich

Ursprünglich: Studium Geographie & Informatik / Tages-Anzeiger

Seit November 2014 beim Team von SRF Data als **Programmierer** und **Datenjournalist** 

---

### SRF Data

![SRF Data](assets/img/srfdata.jpg)

* Mehr Rechercheteam, weniger Dienstleister
* Ideen pitchen, Daten sammeln / rausklagen / bekommen, Story finden
* Publikation in Radio und/oder TV -> Anekdoten / Details / Repos
* Publikation auf srf.ch -> Übersicht, Interaktivität
* [Portfolio](http:/srf.ch/srfdata)

---


### Warum Reproduzierbarkeit?

<aside class="notes">Ohne Reproduzierbarkeit keine echte, vollständige Transparenz. Richtige Reproduzierbarkeit bedingt, dass von den absoluten Rohdaten bis zum (analytischen) Endergebnis alle Schritte nachvollziehbar und ausführbar sind. Eigentlich ist dies nur zu erreichen, wenn man die Schritte "aufzeichnet", und dafür eignet sich am besten Code: Sprich, die Datenanalyse selber besteht aus einem Skript, dass einen Input nimmt und einen Output generiert. Das bringt zwei Vorteile mit sich: Man kann das Skript wiederverwenden, z.B. bei neuen Daten. Und das ganze ist automatisiert, sprich, wir können Kaffee trinken gehen, während der Computer rechnet. Die Automatisierung kann wiederum dabei helfen, Fehler zu vermeiden, die man beim manuellen Bearbeiten, z.B. aus Unkonzentriertheit, machen könnte.</aside>

.fragment 1. Transparenz

.fragment 2. Automatisierung 

.fragment 2b. Wiederverwendbarkeit 

.fragment 2c. Reduzierte Fehleranfälligkeit

--- 

### Genug der Theorie!!! 

<aside class="notes">Im folgenden nun zwei Beispiele, wie wir bei SRF Data konkret versuchen, das zu leben, was ich hier predige.</aside>

![Gute Nacht](assets/img/sleeping.jpg)

<small>Bildquelle: Flickr.com</small>

---

### Wie wir versuchen, transparent zu sein

<aside class="notes">Im selben Zug möchte ich zwei Tools bzw. Ideen präsentieren, wie man mit Technologie Transparenz schaffen kann.</aside>

(und effizient zu arbeiten...)

[R](http://r-project.org) / [RMarkdown](http://rmarkdown.rstudio.com/)

[GitHub](http://github.com)

---

### Beispiel 1: Rüstungsexporte

![Rüstungsexporte](assets/img/notrecht.jpg)

Publizierter Artikel: [Hier](http://www.srf.ch/news/schweiz/notrecht-als-letztes-mittel-gegen-heikle-ruestungsexporte)

Methodik und Rohdaten: [Hier](http://srfdata.github.io/1503-seco-dual-use-goods/)

--> DEMO

---

### Beispiel 1: Rüstungsexporte

* Auswertung der Daten in R:
 * Reinladen
 * Vorprozessieren (messy -> tidy)
 * Erste Auswertungen inkl. Plots
 
* Publikation als Markdown-HTML
* Publikation auf GitHub Pages:
 * Automatisiert über Shell-Skript

---

### Beispiel 2: Wahlen 2015

<aside class="notes">Beispiel P1: Interaktive Visualisierung mit Shiny; Beispiel P3: Vorprozessieren für Entwickler</aside>

![Wahlen](assets/img/wahlen.jpg)

Publizierte Artikel: [Hier](http://www.srf.ch/news/wahlen-15/wahlkampf/so-haben-die-schweizer-gemeinden-seit-1971-gewaehlt) oder [hier](http://www.srf.ch/news/wahlen-15/von-listenglueck-und-proporzpech)

Methodik / interaktive Auswertung: z.B. [hier](https://grssnbchr.shinyapps.io/elections15-project1)

--> DEMO

--- 

### Beispiel 2: Wahlen 2015 

* Vor allem Vorprozessierung für Visualisierung 
* Daten und Methoden wurden noch nicht veröffentlicht, ist aber geplant
* Interaktive Visualisierungen mit Shiny - u.a. für Kollegen (z.B. beim Radio)
* Vorprozessierung von "Hand" kaum vorstellbar
* Und immer wieder:

`git status`

---

### Fazit

**R** ermöglicht uns:

* alle Prozessierungsschritte an einem Ort zu *bündeln*
    * einlesen
    * vorprozessieren
    * auswerten
    * visualisieren
    * vorbereiten
    * etc.
 
* Reproduzierbarkeit & Publikation der Methoden mit **Markdown**

---

### Fazit

**GitHub** ermöglicht uns:

* Austausch von Code und Daten (intern und extern)
* Schnelle Publikation über GitHub Pages
* Versionsvergleiche
    
---

*Wir sind erst am Anfang und probieren viel aus.*<br/>
*Klar ist: Transparenz ist notwendig - und machbar!*

---

## Blut geleckt?

<br/><br/>

[rddj.info - damit bringt Ihr Euch R bei](http://rddj.info)


---

# Danke

## Fragen? 

[@grssnbchr](http://twitter.com/grssnbchr)

[@srfdata](http://twitter.com/srfdata)

Diese Präsentation ist verfügbar (und reproduzierbar) unter [github.com/grssnbchr/nrdl-rddj](https://github.com/grssnbchr/nrdl-rddj/blob/gh-pages/index.md)

<small>Gebaut mit [slidify](https://github.com/ramnathv/slidify) und [revealjs](https://github.com/hakimel/reveal.js/)</small>
