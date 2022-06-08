---
title: Multi-dimensional root cause analysis
summary: Modeling relationship among multi-dimensional cross metrics by graph network and analyze the root cause of the target node. Related work has been accepted by KDD2022.
tags:
  - root cause analysis
date: '2021-08-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#   url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

In large-scale online services, crucial metrics, a.k.a., key performance indicators (KPIs), are monitored periodically to check the running statuses. Generally, KPIs are aggregated along multiple dimensions and derived by complex calculations among fundamental metrics from the raw data. Once abnormal KPI values are observed, root cause analysis (RCA) can be applied to identify the reasons for anomalies, so that we can troubleshoot quickly. Recently, several automatic RCA techniques were proposed to localize the related dimensions (or a combination of dimensions) to explain the anomalies. However, their analyses are limited to the data on the abnormal metric and ignore the data of other metrics which may be also related to the anomalies, leading to imprecise or even incorrect root causes. To this end, we propose a cross-metric multi-dimensional root cause analysis method, named CMMD, which consists of two key components/:1) relationship modeling, which utilizes graph neural network (GNN) to model the unknown complex calculation among metrics and aggregation function among dimensions from historical data; 2) root cause localization, which adopts the genetic algorithm to efficiently and effectively dive into the raw data and localize the abnormal dimension(s) once the KPI anomalies are detected. Experiments on synthetic datasets, public datasets and online production environment demonstrate the superiority of our proposed CMMD method compared with baselines. Currently, CMMD is running as an online service in Microsoft Azure.