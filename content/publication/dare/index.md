---
title: "Density Adaptive Point Set Registration"
authors:
- Felix Järemo Lawin
- admin
- Fahad Shahbaz Khan
- Per-Erik Forssén
- Michael Felsberg

date: "2018-06-20T00:00:00Z"
doi: "10.1109/CVPR.2018.00403"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-06-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer Vision and Pattern Recognition, CVPR 2018*
publication_short: In *CVPR 2018*

abstract: "Probabilistic methods for point set registration have demonstrated competitive results in recent years. These techniques estimate a probability distribution model of the point clouds. While such a representation has shown promise, it is highly sensitive to variations in the density of 3D points. This fundamental problem is primarily caused by changes in the sensor location across point sets. We revisit the foundations of the probabilistic registration paradigm. Contrary to previous works, we model the underlying structure of the scene as a latent probability distribution, and thereby induce invariance to point set density changes. Both the probabilistic model of the scene and the registration parameters are inferred by minimizing the Kullback-Leibler divergence in an Expectation Maximization based framework. Our density-adaptive registration successfully handles severe density variations commonly encountered in terrestrial Lidar applications. We perform extensive experiments on several challenging real-world Lidar datasets. The results demonstrate that our approach outperforms state-of-the-art probabilistic methods for multi-view registration, without the need of re-sampling."

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">CVPR 2018</b> <b style="font-size:120%;color:#E08040">Oral</b><br> Revisiting the foundations of probabilistic point cloud registration in order to tackle the key issue of sampling density variations.
tags:
#- Source Themes
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/1804.01495
#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: 'https://github.com/felja633/DARE'
#url_dataset: '#'
#url_poster: '#'
#url_project: 'https://prunetruong.com/research/gocor'
#url_slides: ''
#url_source: '#'
url_video: 'https://youtu.be/GKAsIh0o1mM?t=106'

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


