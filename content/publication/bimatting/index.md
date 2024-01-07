---
title: "BiMatting: Efficient Video Matting via Binarization"
authors:
- Haotong Qin
- leike
- Xudong Ma
- admin
- Yu-Wing Tai
- Chi-Keung Tang
- Xianglong Liu
- Et al.
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2023-10-01T01:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-10-01T01:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Neural Information Processing Systems, NeurIPS 2023*
publication_short: In *NeurIPS 2023*

abstract: Real-time video matting on edge devices faces significant computational resource constraints, limiting the widespread use of video matting in applications such as online conferences and short-form video production. Binarization is a powerful compression approach that greatly reduces computation and memory consumption by using 1-bit parameters and bitwise operations. However, binarization of the video matting model is not a straightforward process, and our empirical analysis has revealed two primary bottlenecks; severe representation degradation of the encoder and massive redundant computations of the decoder. To address these issues, we propose BiMatting, an accurate and efficient video matting model using binarization. Specifically, we construct shrinkable and dense topologies of the binarized encoder block to enhance the extracted representation. We sparsify the binarized units to reduce the low-information decoding computation. Through extensive experiments, we demonstrate that BiMatting outperforms other binarized video matting models, including state-of-the-art (SOTA) binarization methods, by a significant margin. Our approach even performs comparably to the full-precision counterpart in visual quality. Furthermore, BiMatting achieves remarkable savings of 12.4$\times$ and 21.6$\times$ in computation and storage, respectively, showcasing its potential and advantages in real-world resource-constrained scenarios.

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">NeurIPS 2023</b><br> A binary network for highly efficient video matting.
tags:
#- Source Themes
featured: false

links:
# - name: arXiv
#   url: https://arxiv.org/abs/2009.07823
#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: 'https://github.com/htqin/BiMatting'
#url_dataset: '#'
#url_poster: '#'
# url_project: 'https://prunetruong.com/research/gocor'
#url_slides: ''
#url_source: '#'
# url_video: 'https://youtu.be/V22MyFChBCs'

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


