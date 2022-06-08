---
title: 'Data-Driven Two-Dimensional Deep Correlated Representation Learning for Nonlinear Batch Process Monitoring'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Qingchao Jiang
  - admin
  - Xuefeng Yan
  - Hui Yi
  - Furong Gao


# Author notes (optional)
author_notes:
  - ''
  #'Equal contribution'
  

date: '2020-04-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-04-18T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Industrial Informatics*
publication_short: In *IEEE Trans. Ind. Inform.*

abstract: Dynamics and nonlinearity may exist in the time and batch directions for batch processes, thereby complicating the monitoring of these processes. In this article, we propose a two-dimensional deep correlated representation learning (2D-DCRL) method to achieve the efficient fault detection and isolation of the nonlinear batch processes. Three-way historical data are first unfolded as two-way time-slice data. Second, a stacked autoencoder based deep neural network is constructed to characterize the correlation among the process variables. Considering that the time and batch directions may be dynamic, for each time-slice measurement, a constructed 2-D measurement containing samples from the previous time instants and batches is then obtained. Subsequently, DCRL is performed between the current running-batch measurements and the constructed 2-D measurements to characterize the 2-D dynamics and nonlinearity. The 2D-DCRL-based monitoring examines the status of a sample by considering the 2-D nonlinear and dynamic information, providing improved monitoring performance. Applications on two typical batch processes demonstrate the effectiveness of the proposed 2D-DCRL monitoring scheme.

# Summary. An optional shortened abstract.
summary: Data-Driven Two-Dimensional Deep Correlated Representation Learning for Nonlinear Batch Process Monitoring.

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


