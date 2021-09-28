---
title: "Generating Masks from Boxes by Mining Spatio-Temporal Consistencies in Videos"
authors:
- Bin Zhao
- goutam
- admin
- Luc Van Gool
- Radu Timofte

date: "2021-08-01T04:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-01T04:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Computer Vision, ICCV 2021*
publication_short: In *ICCV 2021*

abstract: "Segmenting objects in videos is a fundamental computer vision task. The current deep learning based paradigm offers a powerful, but data-hungry solution. However, current datasets are limited by the cost and human effort of annotating object masks in videos. This effectively limits the performance and generalization capabilities of existing video segmentation methods. To address this issue, we explore weaker form of bounding box annotations.
<br>
We introduce a method for generating segmentation masks from per-frame bounding box annotations in videos. To this end, we propose a spatio-temporal aggregation module that effectively mines consistencies in the object and background appearance across multiple frames. We use our resulting accurate masks for weakly supervised training of video object segmentation (VOS) networks. We generate segmentation masks for large scale tracking datasets, using only their bounding box annotations. The additional data provides substantially better generalization performance leading to state-of-the-art results in both the VOS and more challenging tracking domain."

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">ICCV 2021</b><br> An optimization-based architecture for converting video bounding box annotations to segmentation masks.
tags:
#- Source Themes
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/2101.02196
#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: 'https://github.com/visionml/pytracking'
#url_dataset: '#'
#url_poster: '#'
#url_project: 'https://prunetruong.com/research/warpc'
#url_slides: ''
#url_source: '#'
#url_video: ''

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


