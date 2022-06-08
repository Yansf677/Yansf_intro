---
title: 'Local–global modeling and distributed computing framework for nonlinear plant-wide process monitoring with industrial big data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Qingchao Jiang
  - admin
  - Hui Cheng
  - Xuefeng Yan


# Author notes (optional)
author_notes:
  - ''
  #'Equal contribution'
  

date: '2020-08-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-08-18T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Neural Networks and Learning Systems*
publication_short: In *IEEE Trans. Neural Netw. Learn. Syst.*

abstract: Industrial big data and complex process nonlinearity have introduced new challenges in plant-wide process monitoring. This article proposes a local-global modeling and distributed computing framework to achieve efficient fault detection and isolation for nonlinear plant-wide processes. First, a stacked autoencoder is used to extract dominant representations of each local process unit and establish the local inner monitor. Second, mutual information (MI) is used to determine the neighborhood variables of a local unit. Afterward, a joint representation learning is then performed between the local unit and the neighborhood variables to extract the outer-related representations and establish the outer-related monitor for the local unit. Finally, the outer-related representations from all process units are used to establish global monitoring systems. Given that the modeling of each unit can be performed individually, the computation process can be efficiently completed with different CPUs. The proposed modeling and monitoring method is applied to the Tennessee Eastman (TE) and laboratory-scale glycerol distillation processes to demonstrate the feasibility of the method.

# Summary. An optional shortened abstract.
summary: Local–global modeling and distributed computing framework for nonlinear plant-wide process monitoring with industrial big data.

tags: ['anomaly detection']

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


