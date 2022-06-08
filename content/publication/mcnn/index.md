---
title: 'Nonlinear quality-relevant process monitoring based on maximizing correlation neural network'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Xuefeng Yan


# Author notes (optional)
author_notes:
  - ''
  #'Equal contribution'
  

date: '2021-03-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-03-18T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Neural Computing and Applications*
publication_short: In *Neural Comput. Appl.*

abstract: Quality-relevant fault detection aims to reveal whether quality variables are affected when a fault is detected. For current industrial processes, kernel-based methods focus on the nonlinearity within process variables, which is insufficient for obtaining nonlinearities of quality variables. Alternatively, neural network is an option for nonlinear prediction. However, these models are driven by predictive errors on samples. For quality-relevant tasks, the key is to capture the trends of quality variables. Therefore, this study proposes a new model, namely, maximizing correlation neural network (MCNN), to predict the quality-relevant information intuitively. The MCNN is trained to maximize the linear correlation between quality variables and the combinations of nonlinear representations mapped by a multilayer feedforward network. As such, fault detection can be implemented in the quality-relevant and irrelevant subspaces on the basis of the deep most correlated representations of process variables. Considering that different variables have different sensitivities to quality at various locations due to their nonlinear relationship, fault backpropagation is designed in the MCNN to isolate the faulty variables on the basis of real-time faulty information. Finally, numerical example and Tennessee Eastman process are used to evaluate the proposed method, which exhibits a competitive performance.

# Summary. An optional shortened abstract.
summary: Nonlinear quality-relevant process monitoring based on maximizing correlation neural network.

tags: ['anomaly detection', 'regression']

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


