---
title: "Probabilistic Warp Consistency for Weakly-Supervised Semantic Correspondences"
authors:
- prune
- admin
- Fisher Yu
- Luc Van Gool

date: "2022-03-01T06:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-01T06:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer Vision and Pattern Recognition, CVPR 2022*
publication_short: In *CVPR 2022*

abstract: "We propose Probabilistic Warp Consistency, a weakly-supervised learning objective for semantic matching. Our approach directly supervises the dense matching scores predicted by the network, encoded as a conditional probability distribution. We first construct an image triplet by applying a known warp to one of the images in a pair depicting different instances of the same object class. Our probabilistic learning objectives are then derived using the constraints arising from the resulting image triplet. We further account for occlusion and background clutter present in real image pairs by extending our probabilistic output space with a learnable unmatched state. To supervise it, we design an objective between image pairs depicting different object classes. We validate our method by applying it to four recent semantic matching architectures. Our weakly-supervised approach sets a new state-of-the-art on four challenging semantic matching benchmarks. Lastly, we demonstrate that our objective also brings substantial improvements in the strongly-supervised regime, when combined with keypoint annotations."

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">CVPR 2022</b><br> A weakly-supervised method for learning dense semantic correspondences.
tags:
#- Source Themes
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/2203.04279
#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: 'https://github.com/PruneTruong/DenseMatching'
#url_dataset: '#'
#url_poster: '#'
url_project: 'https://prunetruong.com/research/pwarpc'
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


