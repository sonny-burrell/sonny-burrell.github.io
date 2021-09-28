---
title: "The Heterogeneity Hypothesis: Finding Layer-Wise Dissimilated Network Architecture"
authors:
- Yawei Li
- Wen Li
- admin
- Kai Zhang
- Shuhang Gu
- Luc Van Gool
- Radu Timofte

date: "2021-03-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer Vision and Pattern Recognition, CVPR 2021*
publication_short: In *CVPR 2021*

abstract: In this paper, we tackle the problem of convolutional neural network design. Instead of focusing on the overall architecture design, we investigate a design space that is usually overlooked, i.e. adjusting the channel configurations of predefined networks. We find that this adjustment can be achieved by pruning widened baseline networks and leads to superior performance. Base on that, we articulate the heterogeneity hypothesis with the same training protocol, there exists a layer-wise dissimilated network architecture (LW-DNA) that can outperform the original network with regular channel configurations under lower level of model complexity. The LW-DNA models are identified without added computational cost and training time compared with the original network. This constraint leads to controlled experiment which directs the focus to the importance of layer-wise specific channel configurations. Multiple sources of hints relate the benefits of LW-DNA models to overfitting, i.e. the relative relationship between model complexity and dataset size. Experiments are conducted on various networks and datasets for image classification, visual tracking and image restoration. The resultant LW-DNA models consistently outperform the compared baseline models.

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">CVPR 2021</b><br> We tackle the problem of convolutional neural network design by adjusting the channel configurations of predefined networks.
tags:
#- Source Themes
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/2006.16242
#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
#url_code: ''
#url_dataset: '#'
#url_poster: '#'
#url_project: 'https://prunetruong.com/research/pdcnet'
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


