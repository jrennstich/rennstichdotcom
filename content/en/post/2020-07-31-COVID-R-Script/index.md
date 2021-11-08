---
title: RKI Nowcast Data R-script
subtitle: R-script to Calculate Covid-19 R Number Based on RKI Nowcast Data
summary: I made some easy-to-run scripts available for people, who want to plot the latest RKI-Nowcast R-estimates themselves. There is a German and an English version.
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

# R-script to Calculate Covid-19 R Number Based on RKI Nowcast Data
The [Robert Koch Institute](https://www.rki.de) in Germany is releasing the most current forecasting of infection rate development of SARS-CoV-2-cases using a tool they call ["Nowcasting"](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/Projekte_RKI/Nowcasting.html). They have also released a [paper](https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/Projekte_RKI/R-Wert-Erlaeuterung.pdf?__blob=publicationFile) in which they publish the [R](https://www.r-project.org/)-code to download the most current data stored in an Excel file and to plot both, the R value itself and the 7-day R-value forecasting estimate.

I was running into trouble simply trying to run the code in my R set-up, so I [made these scripts available](https://github.com/jrennstich/Nowcast_RKI/) for people, who were also struggling to plot the numbers themselves. There is a [German](https://github.com/jrennstich/Nowcast_RKI/blob/master/RKI_R_Nowcast_Script_DE.R) and an [English](https://github.com/jrennstich/Nowcast_RKI/blob/master/RKI_R_Nowcast_Script_EN.R) version. Hope you find it useful.
