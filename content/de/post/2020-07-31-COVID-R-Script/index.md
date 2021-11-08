---
title: RKI Nowcast Data R-script
subtitle: R-script zur Berechnung und graphischen Darstellung der aktuellen Covid-19 R-Werte basierend auf dem RKI Nowcast Datensatz
summary: Ich habe die Scripts des RKI zur Berechnung des aktuellen R-Wertes erweitert, damit auch Personen mit geringen R Kenntnissen diese problemlos laufen lassen und sich Daten herunterladen und die Plots entsprechend selber erstellen können. Es gibt eine englische und deutsche Version.
authors:
  - jkr
tags:
  - r
  - methodology
  - script
categories:
  - methodology
date: "2020-07-31T00:00:00Z"
lastmod: "2020-07-31T12:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 2
  caption: 'Screenshot from Github page'
  focal_point: "Smart"
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: [methods]
---


# R-script zur Berechnung der aktuellen Covid-19 R Werte basierend auf dem RKI Nowcast Datensatz
Das [Robert Koch Institute](https://www.rki.de) in Deutschland veröffentlicht die Berechnungen der Infektionsraten (R-Werte) bezogen SARS-CoV-2-Fälle mit einem Modell namens ["Nowcasting"](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/Projekte_RKI/Nowcasting.html). Das RKI hat ein [Paper](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/Projekte_RKI/R-Wert-Erlaeuterung.pdf?__blob=publicationFile) publiziert, in dem auch der zur Berechnung notwendige [R](https://www.r-project.org/)-Code zum herunterladen der aktuellsten Nowcast Daten und Berechnung der R-Werte und darauf basierende Plots (Graphiken) enthalten ist.

Bei meinem ersten Versuch, diesen Code einfach laufen zu lassen in meinem Set-up schlug leider fehl. Also habe [hier diese Scripts erweitert](https://github.com/jrennstich/Nowcast_RKI/) und dann auch noch weitere hinzugefügt, damit auch Personen mit geringen R Kenntnissen diese problemlos laufen lassen und sich Daten herunterladen und die Plots entsprechend selber erstellen können. Es gibt eine [deutsche](https://github.com/jrennstich/Nowcast_RKI/blob/master/RKI_R_Nowcast_Script_DE.R) und eine [englische](https://github.com/jrennstich/Nowcast_RKI/blob/master/RKI_R_Nowcast_Script_EN.R) Version. Viel Spass damit!
