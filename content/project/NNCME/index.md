---
title: Dynamic behavior modeling of gene based on neural network
summary: Model the stochastic behaviors of gene expression based on neural networks and realize the euralODE algorithm. Related work has been published by Nature Communications，got the Nomination for Outstanding Youth Paper Award at 2021 WAIC.

tags:
  - bioinformatics
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
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

Non-Markovian models of stochastic biochemical kinetics often incorporate explicit time delays to effectively model large numbers of intermediate biochemical processes. Analysis and simulation of these models, as well as the inference of their parameters from data, are fraught with difficulties because the dynamics depends on the system’s history. Here we use an artificial neural network to approximate the time-dependent distributions of non-Markovian models by the solutions of much simpler time-inhomogeneous Markovian models; the approximation does not increase the dimensionality of the model and simultaneously leads to inference of the kinetic parameters. The training of the neural network uses a relatively small set of noisy measurements generated by experimental data or stochastic simulations of the non-Markovian model. We show using a variety of models, where the delays stem from transcriptional processes and feedback control, that the Markovian models learnt by the neural network accurately reflect the stochastic dynamics across parameter space.
