---
title: 'Design teacher and supervised dual stacked auto-encoders for quality-relevant fault detection in industrial process'

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
  

date: '2019-05-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2019-05-18T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Applied Soft Computing*
publication_short: In *Appl. Soft Comput.*

abstract: Current fault detection methods based on deep neural networks only consider process information and ignore quality indicators. In order to obtain features representing both process variables and quality indicators efficiently, this paper designs teacher and supervise dual stacked auto-encoder (TSSAE) for quality-relevant fault detection in industrial process which separates the feature extraction and model construction. To separate the feature extraction and model construction, a mixing stacked auto-encoder which consists of a nonlinear encoder and a linear decoder is designed to extract features of process variables and quality indicators. Another encoder is supervised by the extracted features and further predict the process variables and quality indicators only from process variables. Then quality-relevant, quality-irrelevant and residual subspaces are constructed in a linear way and fault detection is implemented.

# Summary. An optional shortened abstract.
summary: Design teacher and supervised dual stacked auto-encoders for quality-relevant fault detection in industrial process.

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


