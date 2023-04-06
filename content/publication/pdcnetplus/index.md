---
title: "PDC-Net+: Enhanced Probabilistic Dense Correspondence Network"
authors:
- prune
- admin
- Luc Van Gool
- Radu Timofte

date: "2023-03-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Transactions on Pattern Analysis and Machine Intelligence, TPAMI 2023*
publication_short: In *TPAMI 2023*

abstract: "Establishing robust and accurate correspondences between a pair of images is a long-standing computer vision problem with numerous applications. While classically dominated by sparse methods, emerging dense approaches offer a compelling alternative paradigm that avoids the keypoint detection step. However, dense flow estimation is often inaccurate in the case of large displacements, occlusions, or homogeneous regions. In order to apply dense methods to real-world applications, such as pose estimation, image manipulation, or 3D reconstruction, it is therefore crucial to estimate the confidence of the predicted matches.

We propose the Enhanced Probabilistic Dense Correspondence Network, PDC-Net+, capable of estimating accurate dense correspondences along with a reliable confidence map. We develop a flexible probabilistic approach that jointly learns the flow prediction and its uncertainty. In particular, we parametrize the predictive distribution as a constrained mixture model, ensuring better modelling of both accurate flow predictions and outliers. Moreover, we develop an architecture and an enhanced training strategy tailored for robust and generalizable uncertainty prediction in the context of self-supervised training. Our approach obtains state-of-the-art results on multiple challenging geometric matching and optical flow datasets. We further validate the usefulness of our probabilistic confidence estimation for the tasks of pose estimation, 3D reconstruction, image-based localization, and image retrieval."

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">TPAMI 2023</b><br> A method that gives you accurate dense optical flow and correspondences with robust uncertainty.
tags:
#- Source Themes
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/2109.13912
#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: 'https://github.com/PruneTruong/DenseMatching'
#url_dataset: '#'
#url_poster: '#'
url_project: 'https://prunetruong.com/research/pdcnet+'
#url_slides: ''
#url_source: '#'
# url_video: 'https://youtu.be/bX0rEaSf88o'

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


