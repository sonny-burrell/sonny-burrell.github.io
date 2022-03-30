---
title: "Adiabatic Quantum Computing for Multi Object Tracking"
authors:
- nico
- Alexander Liniger
- admin
- Dengxin Dai
- Luc Van Gool

date: "2022-03-01T05:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-01T05:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer Vision and Pattern Recognition, CVPR 2022*
publication_short: In *CVPR 2022*

abstract: "Multi-Object Tracking (MOT) is most often approached in the tracking-by-detection paradigm, where object detections are associated through time. The association step naturally leads to discrete optimization problems. As these optimization problems are often NP-hard, they can only be solved exactly for small instances on current hardware. Adiabatic quantum computing (AQC) offers a solution for this, as it has the potential to provide a considerable speedup on a range of NP-hard optimization problems in the near future. However, current MOT formulations are unsuitable for quantum computing due to their scaling properties. In this work, we therefore propose the first MOT formulation designed to be solved with AQC. We employ an Ising model that represents the quantum mechanical system implemented on the AQC. We show that our approach is competitive compared with state-of-the-art optimization-based approaches, even when using of-the-shelf integer programming solvers. Finally, we demonstrate that our MOT problem is already solvable on the current generation of real quantum computers for small examples, and analyze the properties of the measured solutions."

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">CVPR 2022</b><br> A Multi-Object Tracking algorithm that can be solved with Adiabatic Quantum Computing
tags:
#- Source Themes
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/2202.08837
#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
# url_code: 'https://github.com/PruneTruong/DenseMatching'
#url_dataset: '#'
#url_poster: '#'
# url_project: 'https://prunetruong.com/research/pwarpc'
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


