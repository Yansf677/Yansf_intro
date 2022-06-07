---
title: 'CMMD: Cross-Metric Multi-Dimensional Root Cause Analysis'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Caihua Shan
  - Wenyi Yang
  - Bixiong Xu
  - Dongsheng Li
  - Lili Qiu
  - Jie Tong
  - Qi Zhang

# Author notes (optional)
author_notes:
  - ''
  # - 'Equal contribution'

date: '2022-05-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-05-18T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *The 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining*
publication_short: In *KDD*

abstract: In large-scale online services, crucial metrics, a.k.a., key performance indicators (KPIs), are monitored periodically to check the running statuses. Generally, KPIs are aggregated along multiple dimensions and derived by complex calculations among fundamental metrics from the raw data. Once abnormal KPI values are observed, root cause analysis (RCA) can be applied to identify the reasons for anomalies, so that we can troubleshoot quickly. Recently, several automatic RCA techniques were proposed to localize the related dimensions (or a combination of dimensions) to explain the anomalies. However, their analyses are limited to the data on the abnormal metric and ignore the data of other metrics which may be also related to the anomalies, leading to imprecise or even incorrect root causes. To this end, we propose a cross-metric multi-dimensional root cause analysis method, named CMMD, which consists of two key components/:1) relationship modeling, which utilizes graph neural network (GNN) to model the unknown complex calculation among metrics and aggregation function among dimensions from historical data; 2) root cause localization, which adopts the genetic algorithm to efficiently and effectively dive into the raw data and localize the abnormal dimension(s) once the KPI anomalies are detected. Experiments on synthetic datasets, public datasets and online production environment demonstrate the superiority of our proposed CMMD method compared with baselines. Currently, CMMD is running as an online service in Microsoft Azure.

# Summary. An optional shortened abstract.
summary: Cross-Metric Multi-Dimensional Root Cause Analysis.

tags: ['root cause analysis']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example

# Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}


