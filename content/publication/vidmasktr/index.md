---
title: "Video Mask Transfiner for High-Quality Video Instance Segmentation"
authors:
- Lei Ke
- Henghui Ding
- admin
- Yu-Wing Tai
- Chi-Keung Tang
- Fisher Yu

date: "2022-08-01T04:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-08-01T04:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *European Conference on Computer Vision, ECCV 2022*
publication_short: In *ECCV 2022*

abstract: "While Video Instance Segmentation (VIS) has seen rapid progress, current approaches struggle to predict high-quality masks with accurate boundary details. Moreover, the predicted segmentations often fluctuate over time, suggesting that temporal consistency cues are neglected or not fully utilized. In this paper, we set out to tackle these issues, with the aim of achieving highly detailed and more temporally stable mask predictions for VIS. We first propose the Video Mask Transfiner (VMT) method, capable of leveraging fine-grained high-resolution features thanks to a highly efficient video transformer structure. Our VMT detects and groups sparse error-prone spatio-temporal regions of each tracklet in the video segment, which are then refined using both local and instance-level cues. Second, we identify that the coarse boundary annotations of the popular YouTube-VIS dataset constitute a major limiting factor. Based on our VMT architecture, we therefore design an automated annotation refinement approach by iterative training and self-correction. To benchmark high-quality mask predictions for VIS, we introduce the HQ-YTVIS dataset, consisting of a manually re-annotated test set and our automatically refined training data. We compare VMT with the most recent state-of-the-art methods on the HQ-YTVIS, as well as the Youtube-VIS, OVIS and BDD100K MOTS benchmarks. Experimental results clearly demonstrate the efficacy and effectiveness of our method on segmenting complex and dynamic objects, by capturing precise details."

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">ECCV 2022</b><br> An efficient transformer-based method for highly accurate video instance segmentation.
tags:
#- Source Themes
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/2207.14012
#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: 'https://github.com/SysCV/vmt'
url_dataset: 'https://www.vis.xyz/data/hqvis/'
#url_poster: '#'
url_project: 'https://www.vis.xyz/pub/vmt/'
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


