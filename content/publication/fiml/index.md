---
title: "Few-Shot Classification By Few-Iteration Meta-Learning"
authors:
- ardhendu
- admin
- Luc Van Gool
- Radu Timofte

date: "2021-03-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Robotics and Automation, ICRA 2021*
publication_short: In *ICRA 2021*

abstract: Learning in a low-data regime from only a few labeled examples is an important, but challenging problem. Recent advancements within meta-learning have demonstrated encouraging performance, in particular, for the task of few-shot classification. We propose a novel optimization-based meta-learning approach for few-shot classification. It consists of an embedding network, providing a general representation of the image, and a base learner module. The latter learns a linear classifier during the inference through an unrolled optimization procedure. We design an inner learning objective composed of (i) a robust classification loss on the support set and (ii) an entropy loss, allowing transductive learning from unlabeled query samples. By employing an efficient initialization module and a Steepest Descent based optimization algorithm, our base learner predicts a powerful classifier within only a few iterations. Further, our strategy enables important aspects of the base learner objective to be learned during meta-training. To the best of our knowledge, this work is the first to integrate both induction and transduction into the base learner in an optimization-based meta-learning framework. We perform a comprehensive experimental analysis, demonstrating the effectiveness of our approach on four few-shot classification datasets.

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">ICRA 2021</b><br> An optimization-based meta-learning approach for few-shot classification. 
tags:
#- Source Themes
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/2010.00511
#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: 'https://github.com/4rdhendu/FIML'
#url_dataset: '#'
#url_poster: '#'
#url_project: 'https://prunetruong.com/research/pdcnet'
#url_slides: ''
#url_source: '#'
url_video: 'https://youtu.be/C0m2OT5to5s'

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


