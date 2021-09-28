---
title: "Adaptive Decontamination of the Training Set: A Unified Formulation for Discriminative Visual Tracking"
authors:
- admin
- Gustav Häger
- Fahad Shahbaz Khan
- Michael Felsberg

date: "2016-06-24T00:00:00Z"
doi: "10.1109/CVPR.2016.159"

# Schedule page publish date (NOT publication's date).
publishDate: "2016-06-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer Vision and Pattern Recognition, CVPR 2016*
publication_short: In *CVPR 2016*

abstract: "Tracking-by-detection methods have demonstrated competitive performance in recent years. In these approaches, the tracking model heavily relies on the quality of the training set. Due to the limited amount of labeled training data, additional samples need to be extracted and labeled by the tracker itself. This often leads to the inclusion of corrupted training samples, due to occlusions, misalignments and other perturbations. Existing tracking-by-detection methods either ignore this problem, or employ a separate component for managing the training set.
We propose a novel generic approach for alleviating the problem of corrupted training samples in tracking-by-detection frameworks. Our approach dynamically manages the training set by estimating the quality of the samples. Contrary to existing approaches, we propose a unified formulation by minimizing a single loss over both the target appearance model and the sample quality weights. The joint formulation enables corrupted samples to be down-weighted while increasing the impact of correct ones. Experiments are performed on three benchmarks: OTB-2015 with 100 videos, VOT-2015 with 60 videos, and Temple-Color with 128 videos. On the OTB-2015, our unified formulation significantly improves the baseline, with a gain of 3.8% in mean overlap precision. Finally, our method achieves state-of-the-art results on all three datasets. "

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">CVPR 2016</b> <b style="font-size:120%;color:#E08040"></b><br> A unified formulation for alleviating the problem of corrupted training samples in tracking-by-detection methods.
tags:
#- Source Themes
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/1609.06118
- name: Supplementary
  url: 'files/AdaptiveDecon_CVPR16_suppl.pdf'
- name: Raw Results
  url: files/SRDCFdecon_raw_results.zip
#url_pdf: 'files/ColoredPointReg_CVPR16.pdf'
url_code: 'files/SRDCFdecon_code.zip'
#url_dataset: '#'
#url_poster: '#'
#url_project: 'https://prunetruong.com/research/gocor'
#url_slides: ''
#url_source: '#'
#url_video: 'https://youtu.be/GKAsIh0o1mM?t=106'

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


