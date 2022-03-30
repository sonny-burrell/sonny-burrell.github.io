---
title: "Learnable Online Graph Representations for 3D Multi-Object Tracking"
authors:
- nico
- Dengxin Dai
- Alexander Liniger
- admin
- Luc Van Gool

date: "2022-01-15T05:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-15T05:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Robotics and Automation, ICRA 2022*
publication_short: In *ICRA 2022*

abstract: "Tracking of objects in 3D is a fundamental task in computer vision that finds use in a wide range of applications such as autonomous driving, robotics or augmented reality. Most recent approaches for 3D multi object tracking (MOT) from LIDAR use object dynamics together with a set of handcrafted features to match detections of objects. However, manually designing such features and heuristics is cumbersome and often leads to suboptimal performance. In this work, we instead strive towards a unified and learning based approach to the 3D MOT problem. We design a graph structure to jointly process detection and track states in an online manner. To this end, we employ a Neural Message Passing network for data association that is fully trainable. Our approach provides a natural way for track initialization and handling of false positive detections, while significantly improving track stability. We show the merit of the proposed approach on the publicly available nuScenes dataset by achieving state-of-the-art performance of 65.6% AMOTA and 58% fewer ID-switches."

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">ICRA 2022</b><br> An online 3D Multi-Object Tracking method based on graph neural networks.
tags:
#- Source Themes
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/2104.11747
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


