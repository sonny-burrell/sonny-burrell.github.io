---
title: "GLU-Net: Global-Local Universal Network for Dense Flow and Correspondences"
authors:
- prune
- admin
- Radu Timofte

date: "2020-06-21T00:00:00Z"
doi: "10.1109/CVPR42600.2020.00629"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-21T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer Vision and Pattern Recognition, CVPR 2020*
publication_short: In *CVPR 2020*

abstract: "Establishing dense correspondences between a pair of images is an important and general problem, covering geometric matching, optical flow and semantic correspondences. While these applications share fundamental challenges, such as large displacements, pixel-accuracy, and appearance changes, they are currently addressed with specialized network architectures, designed for only one particular task. This severely limits the generalization capabilities of such networks to new scenarios, where e.g. robustness to larger displacements or higher accuracy is required.
In this work, we propose a universal network architecture that is directly applicable to all the aforementioned dense correspondence problems. We achieve both high accuracy and robustness to large displacements by investigating the combined use of global and local correlation layers. We further propose an adaptive resolution strategy, allowing our network to operate on virtually any input image resolution. The proposed GLU-Net achieves state-of-the-art performance for geometric and semantic matching as well as optical flow, when using the same network and weights."

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">CVPR 2020</b> <b style="font-size:120%;color:#E08040">Oral</b><br> A unified network architecture for dense correspondences applicable to geometric matching, optical flow and semantic matching.
tags:
#- Source Themes
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/1912.05524
#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: 'https://github.com/PruneTruong/GLU-Net'
#url_dataset: '#'
#url_poster: '#'
url_project: 'https://prunetruong.com/research/glu-net'
#url_slides: ''
#url_source: '#'
url_video: 'https://www.youtube.com/watch?v=xB2gNx8f8Xc&feature=emb_title'

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


