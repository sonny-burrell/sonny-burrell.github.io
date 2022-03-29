---
title: "Prototypical Cross-Attention Networks for Multiple Object Tracking and Segmentation"
authors:
- Lei Ke
- Xia Li
- admin
- Yu-Wing Tai
- Chi-Keung Tang
- Fisher Yu
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2021-09-27T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-09-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Neural Information Processing Systems, NeurIPS 2021*
publication_short: In *NeurIPS 2021*

abstract: Multiple object tracking and segmentation requires detecting, tracking, and segmenting objects belonging to a set of given classes. Most approaches only exploit the temporal dimension to address the association problem, while relying on single frame predictions for the segmentation mask itself. We propose Prototypical Cross-Attention Network (PCAN), capable of leveraging rich spatio-temporal information for online multiple object tracking and segmentation. PCAN first distills a space-time memory into a set of prototypes and then employs cross-attention to retrieve rich information from the past frames. To segment each object, PCAN adopts a prototypical appearance module to learn a set of contrastive foreground and background prototypes, which are then propagated over time. Extensive experiments demonstrate that PCAN outperforms current video instance tracking and segmentation competition winners on both Youtube-VIS and BDD100K datasets, and shows efficacy to both one-stage and two-stage segmentation frameworks.

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">NeurIPS 2021</b> <b style="font-size:120%;color:#E08040">Spotlight</b><br> Efficient cross-attention for video instance segmentation. 
tags:
#- Source Themes
featured: true

links:
- name: arXiv
  url: https://arxiv.org/abs/2106.11958
#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
# url_code: 'https://github.com/alexandre01/deepsvg'
#url_dataset: '#'
#url_poster: '#'
# url_project: 'https://blog.alexandrecarlier.com/deepsvg/'
#url_slides: ''
#url_source: '#'
url_video: 'https://youtu.be/Vt-kYDPfh10'

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


