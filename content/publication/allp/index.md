---
title: 'Quality-relevant fault detection based on adversarial learning and distinguished contribution of latent variables to quality'

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
  

date: '2021-10-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-10-18T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Journal of Manufacturing Systems*
publication_short: In *J. Manu. Sys.*

abstract: Quality-relevant fault detection is a primary task to reveal the changes of quality variables in process monitoring. Current works mainly focus on learning quality-relevant features, however, how to distinguish quality-relevant and irrelevant information is responsible for the excellent monitoring performance. In this study, a novel quality-relevant fault detection method is proposed on the basis of adversarial learning and distinguished contribution of latent features to quality is originally introduced. First of all, we map the input variables into a gaussian manifold in adversarial and unsupervised manner. Then a fully connected neural network is trained to learn the relationship between latent and quality variables. To distinguish necessary information in such manifold, the Jacobi operator at the corresponding point is calculated to project the latent variables into quality-relevant and quality-irrelevant subspaces. Third, fault detection is implemented in these dynamic subspaces using the probabilities of latent variables. Finally, the proposed method is evaluated by numerical example, the Tennessee-Eastman process and wind turbine blade icing process.

# Summary. An optional shortened abstract.
summary: Quality-relevant fault detection based on adversarial learning and distinguished contribution of latent variables to quality.

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


