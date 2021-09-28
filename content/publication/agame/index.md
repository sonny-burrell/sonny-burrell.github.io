---
title: "A Generative Appearance Model for End-to-end Video Object Segmentation"
authors:
- joakim
- admin
- Emil Brissman
- Fahad Shahbaz Khan
- Michael Felsberg

date: "2019-06-24T00:00:00Z"
doi: "10.1109/CVPR.2019.00916"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-06-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer Vision and Pattern Recognition, CVPR 2019*
publication_short: In *CVPR 2019*

abstract: "One of the fundamental challenges in video object segmentation is to find an effective representation of the target and background appearance. The best performing approaches resort to extensive fine-tuning of a convolutional neural network for this purpose. Besides being prohibitively expensive, this strategy cannot be truly trained end-to-end since the online fine-tuning procedure is not integrated into the offline training of the network.
To address these issues, we propose a network architecture that learns a powerful representation of the target and background appearance in a single forward pass. The introduced appearance module learns a probabilistic generative model of target and background feature distributions. Given a new image, it predicts the posterior class probabilities, providing a highly discriminative cue, which is processed in later network modules. Both the learning and prediction stages of our appearance module are fully differentiable, enabling true end-to-end training of the entire segmentation pipeline. Comprehensive experiments demonstrate the effectiveness of the proposed approach on three video object segmentation benchmarks. We close the gap to approaches based on online fine-tuning on DAVIS17, while operating at 15 FPS on a single GPU. Furthermore, our method outperforms all published approaches on the large-scale YouTube-VOS dataset."

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">CVPR 2019</b> <b style="font-size:120%;color:#E08040">Oral</b><br> A generative appearance module for end-to-end VOS.
tags:
#- Source Themes
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/1811.11611
#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: 'https://github.com/joakimjohnander/agame-vos'
#url_dataset: '#'
#url_poster: '#'
#url_project: 'https://prunetruong.com/research/gocor'
#url_slides: ''
#url_source: '#'
url_video: 'https://www.youtube.com/watch?v=Vte9QaXEP_w&t=4970s'

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


