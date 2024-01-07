---
title: "QuantSR: Accurate Low-bit Quantization for Efficient Image Super-Resolution"
authors:
- Haotong Qin
- Yulun Zhang
- Yifu Ding
- Yifan Liu
- Xianglong Liu
- admin
- Et al.
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2023-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Neural Information Processing Systems, NeurIPS 2023*
publication_short: In *NeurIPS 2023*

abstract: Low-bit quantization in image super-resolution (SR) has attracted copious attention in recent research due to its ability to reduce parameters and operations significantly. However, many quantized SR models suffer from accuracy degradation compared to their full-precision counterparts, especially at ultra-low bit widths (2-4 bits), limiting their practical applications. To address this issue, we propose a novel quantized image SR network, called QuantSR, which achieves accurate and efficient SR processing under low-bit quantization. To overcome the representation homogeneity caused by quantization in the network, we introduce the Redistribution-driven Learnable Quantizer (RLQ). This is accomplished through an inference-agnostic efficient redistribution design, which adds additional information in both forward and backward passes to improve the representation ability of quantized networks. Furthermore, to achieve flexible inference and break the upper limit of accuracy, we propose the Depth-dynamic Quantized Architecture (DQA). Our DQA allows for the trade-off between efficiency and accuracy during inference through weight sharing. Our comprehensive experiments show that QuantSR outperforms existing state-of-the-art quantized SR networks in terms of accuracy while also providing more competitive computational efficiency. In addition, we demonstrate the scheme's satisfactory architecture generality by providing QuantSR-C and QuantSR-T for both convolution and Transformer versions, respectively.

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">NeurIPS 2023</b><br> Quantization method and architecture for super-resolution.
tags:
#- Source Themes
featured: false

links:
# - name: arXiv
#   url: https://arxiv.org/abs/2009.07823
#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: 'https://github.com/htqin/QuantSR'
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


