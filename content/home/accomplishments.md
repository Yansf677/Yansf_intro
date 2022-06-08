---
# An instance of the Accomplishments widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: accomplishments

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

# Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
title: 'Honors'
subtitle:

# Date format
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Accomplishments.
#   Add/remove as many `item` blocks below as you like.
#   `title`, `organization`, and `date_start` are the required parameters.
#   Leave other parameters empty if not required.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.

item:
  - date_start: '2022-06-20'
    title: Outstanding PhD Graduate
    organization: East China University of Science and Technology
  - date_start: '2021-03-01'
    date_end: '2021-05-20'
    title: Global AI Innovation Contest - Anomaly detection of Medical report (rank/:0.3%)
    organization: Chinese Society for Artificial Intelligence
    description: # Aim to determine whether there are abnormalities in several target areas of the body based on the descriptive text data of CT images. The structure of models is Embedding + BiLSTM + Attention/Shortcut/Pooling that are trained with data enhancement, the strategy of learning rate set in stages, and model integration
  - date_start: '2021-01-01'
    date_end: '2021-03-20'
    title: National Digital Ecological Innovation Competition (rank/:Top 0.5%)
    organization: TianChi
    description: # Aim to identify the land types based on remote sensing image data, image segmentation technology. The model adopts the UNET framework, uses ResNet50 for feature extraction, and BCE+Dice as the loss function. The learning rate is set by the cosine annealing method for training, and the sample is scaled and rotated during testing
  - date_start: '2020-12-01'
    date_end: '2021-01-20'
    title: Guangdong Intelligent Manufacturing Innovation Competition (rank/:Top 1%)
    organization: TianChi
    description: # Aim to Develop an efficient detection algorithm to improve the effect and efficiency of the quality inspection of ceramic tile surface defects. The model adopts the structure of Faster RCNN + FPN, uses ResNet50 as the backbone for feature extraction, and combines template information. The image is scaled to different multiples and the results are merged
  - date_start: '2020-12-20'
    title: National Second Prize at “Huawei Cup” Graduate Mathematical Modeling Contest
    organization: Huawei Inc.
  - date_start: '2020-08-20'
    title: CSC Fellowship
    organization: China Scholarship Council
  - date_start: '2019-09-20'
    date_end: '2020-09-20'
    title: Zhangjiangshu PhD Fellowship
    organization: East China University of Science and Technology
  - date_start: '2014-09-20'
    date_end: '2019-09-20'
    title: Outstanding student award
    organization: East China University of Science and Technology
  - date_start: '2014-09-20'
    date_end: '2019-09-20'
    title: First prize, Academic scholarship
    organization: East China University of Science and Technology
  - date_start: '2017-07-01'
    title: Shanghai Outstanding BSc Graduate
    organization: Shanghai Municipal Education Commission
  - date_start: '2016-09-01'
    title: National Scholarshiop
    organization: Ministry of Education
  - date_start: '2016-08-01'
    title: National First Prize at “AB Cup” National Automation Application Competition
    organization: Rockwell Inc.
  - date_start: '2015-09-01'
    title: Shanghai Scholarshiop
    organization: Shanghai Municipal Education Commission

  #- certificate_url: https://www.coursera.org
  #  date_end: ''
  #  date_start: '2021-01-25'
  #  description: ''
  #  organization: Coursera
  #  organization_url: https://www.coursera.org
  #  title: Neural Networks and Deep Learning
  #  url: ''
  #- certificate_url: https://www.edx.org
  #  date_end: ''
  #  date_start: '2021-01-01'
  #  description: Formulated informed blockchain models, hypotheses, and use cases.
  #  organization: edX
  #  organization_url: https://www.edx.org
  #  title: Blockchain Fundamentals
  #  url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #- certificate_url: https://www.datacamp.com
  #  date_end: '2020-12-21'
  #  date_start: '2020-07-01'
  #  description: ''
  #  organization: DataCamp
  #  organization_url: https://www.datacamp.com
  #  title: 'Object-Oriented Programming in R'
  #  url: ''

design:
  columns: '2'

active: true
---
