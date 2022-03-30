---
title: "Mask Transfiner for High-Quality Instance Segmentation"
authors:
- Lei Ke
- admin
- Xia Li
- Yu-Wing Tai
- Chi-Keung Tang
- Fisher Yu

date: "2022-03-01T07:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-01T07:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer Vision and Pattern Recognition, CVPR 2022*
publication_short: In *CVPR 2022*

abstract: "Two-stage and query-based instance segmentation methods have achieved remarkable results. However, their segmented masks are still very coarse. In this paper, we present Mask Transfiner for high-quality and efficient instance segmentation. Instead of operating on regular dense tensors, our Mask Transfiner decomposes and represents the image regions as a quadtree. Our transformer-based approach only processes detected error-prone tree nodes and self-corrects their errors in parallel. While these sparse pixels only constitute a small proportion of the total number, they are critical to the final mask quality. This allows Mask Transfiner to predict highly accurate instance masks, at a low computational cost. Extensive experiments demonstrate that Mask Transfiner outperforms current instance segmentation methods on three popular benchmarks, significantly improving both two-stage and query-based frameworks by a large margin of +3.0 mask AP on COCO and BDD100K, and +6.6 boundary AP on Cityscapes."

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">CVPR 2022</b><br> An efficient transformer-based method for highly accurate instance segmentation.
tags:
#- Source Themes
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/2111.13673
#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: 'https://github.com/SysCV/transfiner'
#url_dataset: '#'
#url_poster: '#'
url_project: 'https://www.vis.xyz/pub/transfiner/'
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


