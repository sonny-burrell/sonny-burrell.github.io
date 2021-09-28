---
title: "Learning Human-Object Interaction Detection using Interaction Points"
authors:
- Tiancai Wang
- Tong Yang
- admin
- Fahad Shahbaz Khan
- Xiangyu Zhang
- Jian Sun

date: "2020-06-18T00:00:00Z"
doi: "10.1109/CVPR42600.2020.00417"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer Vision and Pattern Recognition, CVPR 2020*
publication_short: In *CVPR 2020*

abstract: "Understanding interactions between humans and objects is one of the fundamental problems in visual classification and an essential step towards detailed scene understanding. Human-object interaction (HOI) detection strives to localize both the human and an object as well as the identification of complex interactions between them. Most existing HOI detection approaches are instance-centric where interactions between all possible human-object pairs are predicted based on appearance features and coarse spatial information. We argue that appearance features alone are insufficient to capture complex human-object interactions. In this paper, we therefore propose a novel fully-convolutional approach that directly detects the interactions between human-object pairs. Our network predicts interaction points, which directly localize and classify the inter-action. Paired with the densely predicted interaction vectors, the interactions are associated with human and object detections to obtain final predictions. To the best of our knowledge, we are the first to propose an approach where HOI detection is posed as a keypoint detection and grouping problem. Experiments are performed on two popular benchmarks: V-COCO and HICO-DET. Our approach sets a new state-of-the-art on both datasets."

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">CVPR 2020</b> <b style="font-size:120%;color:#E08040"></b><br> A fully-convolutional approach that directly detects the interactions between human-object pairs. 
tags:
#- Source Themes
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/2003.14023
#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: 'https://github.com/vaesl/IP-Net'
#url_dataset: '#'
#url_poster: '#'
#url_project: 'https://prunetruong.com/research/glu-net'
#url_slides: ''
#url_source: '#'
url_video: 'https://www.youtube.com/watch?v=RvmePEvKLqM'

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


