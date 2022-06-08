---
title: 'Using Labeled Autoencoder to Supervise Neural Network Combined with k-Nearest Neighbor for Visual Industrial Process Monitoring'

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
  

date: '2019-06-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2019-06-18T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Industrial & Engineering Chemistry Research*
publication_short: In *Ind. Eng. Chem. Reas*

abstract: Data clustering and visualization are efficient methods for visual industrial process monitoring. Self-organizing map (SOM) and t-distributed stochastic neighbor embedding (t-SNE) are two of the most widely used algorithms. However, these methods do not make full use of label information. This paper presents a new strategy that uses labeled autoencoder (LAE) to supervise a neural network (NN) combined with k-nearest neighbor (kNN) for visual process monitoring. The LAE, trained simultaneously by process variables together with corresponding labels, extracts 2D features that are visualized. Then a feedforward NN is supervised by these features to reproduce the clustering results from process variables. After data clustering and visualization are implemented, the decision plane is further established using kNN for online process monitoring. In this way, the category of a new sample can be intuitively predicted based on the projected area on such a plane. For data with excessive categories, multilayer decision plane can be created one by one using multiple LAEs and NNs. The proposed strategy achieves satisfactory results on different cases of the Tennessee-Eastman process.

# Summary. An optional shortened abstract.
summary: Using Labeled Autoencoder to Supervise Neural Network Combined with k-Nearest Neighbor for Visual Industrial Process Monitoring.

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


