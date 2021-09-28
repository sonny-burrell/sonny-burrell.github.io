---
title: "Learning Fast and Robust Target Models for Video Object Segmentation"
authors:
- Andreas Robinson
- Felix Järemo Lawin
- admin
- Fahad Shahbaz Khan
- Michael Felsberg
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2020-06-20T00:00:00Z"
doi: "10.1109/CVPR42600.2020.00743"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer Vision and Pattern Recognition, CVPR 2020*
publication_short: In *CVPR 2020*

abstract: Video object segmentation (VOS) is a highly challenging problem since the initial mask, defining the target object, is only given at test-time. The main difficulty is to effectively handle appearance changes and similar background objects, while maintaining accurate segmentation. Most previous approaches fine-tune segmentation networks on the first frame, resulting in impractical frame-rates and risk of overfitting. More recent methods integrate generative target appearance models, but either achieve limited robustness or require large amounts of training data.<br> We propose a novel VOS architecture consisting of two network components. The target appearance model consists of a light-weight module, which is learned during the inference stage using fast optimization techniques to predict a coarse but robust target segmentation. The segmentation model is exclusively trained offline, designed to process the coarse scores into high quality segmentation masks. Our method is fast, easily trainable and remains highly effective in cases of limited training data. We perform extensive experiments on the challenging YouTube-VOS and DAVIS datasets. Our network achieves favorable performance, while operating at higher frame-rates compared to state-of-the-art.

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">CVPR 2020</b> <b style="font-size:120%;color:#E08040">Oral</b><br> A light-weight optimization-based target model for fast VOS. 
tags:
#- Source Themes
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/2003.00908
#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: 'https://github.com/andr345/frtm-vos'
#url_dataset: '#'
#url_poster: '#'
#url_project: 'https://prunetruong.com/research/gocor'
#url_slides: ''
#url_source: '#'
url_video: 'https://www.youtube.com/watch?v=RxwsWKKp7RI'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---


