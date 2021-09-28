---
title: "A Probabilistic Framework for Color-Based Point Set Registration"
authors:
- admin
- Giulia Meneghetti
- Fahad Shahbaz Khan
- Michael Felsberg

date: "2016-06-25T00:00:00Z"
doi: "10.1109/CVPR.2016.201"

# Schedule page publish date (NOT publication's date).
publishDate: "2016-06-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer Vision and Pattern Recognition, CVPR 2016*
publication_short: In *CVPR 2016*

abstract: "In recent years, sensors capable of measuring both color and depth information have become increasingly popular. Despite the abundance of colored point set data, state-of-the-art probabilistic registration techniques ignore the available color information. In this paper, we propose a probabilistic point set registration framework that exploits available color information associated with the points. Our method is based on a model of the joint distribution of 3D-point observations and their color information. The proposed model captures discriminative color information, while being computationally efficient. We derive an EM algorithm for jointly estimating the model parameters and the relative transformations.

Comprehensive experiments are performed on the Stanford Lounge dataset, captured by an RGB-D camera, and two point sets captured by a Lidar sensor. Our results demonstrate a significant gain in robustness and accuracy when incorporating color information. On the Stanford Lounge dataset, our approach achieves a relative reduction of the failure rate by 78% compared to the baseline. Furthermore, our proposed model outperforms standard strategies for combining color and 3D-point information, leading to state-of-the-art results."

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">CVPR 2016</b> <b style="font-size:120%;color:#E08040"></b><br> A probabilistic point set registration framework that exploits available color information associated with the points.
tags:
#- Source Themes
featured: false

links:
#- name: arXiv
#  url: https://arxiv.org/abs/1804.01495
- name: Supplementary
  url: 'files/ColoredPointReg_CVPR16_suppl.pdf'
- name: Code (unofficial)
  url: 'https://github.com/felja633/DARE'
url_pdf: 'files/ColoredPointReg_CVPR16.pdf'
#url_code: 'https://github.com/felja633/DARE'
#url_dataset: '#'
#url_poster: '#'
#url_project: 'https://prunetruong.com/research/gocor'
#url_slides: ''
#url_source: '#'
#url_video: 'https://youtu.be/GKAsIh0o1mM?t=106'

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


