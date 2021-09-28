---
title: "Learning Spatially Regularized Correlation Filters for Visual Tracking"
authors:
- admin
- Gustav Häger
- Fahad Shahbaz Khan
- Michael Felsberg

date: "2015-12-15T00:00:00Z"
doi: "10.1109/ICCV.2015.490"

# Schedule page publish date (NOT publication's date).
publishDate: "2015-12-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Computer Vision, ICCV 2015*
publication_short: In *ICCV 2015*

abstract: "Robust and accurate visual tracking is one of the most challenging computer vision problems. Due to the inherent lack of training data, a robust approach for constructing a target appearance model is crucial. Recently, discriminatively learned correlation filters (DCF) have been successfully applied to address this problem for tracking. These methods utilize a periodic assumption of the training samples to efficiently learn a classifier on all patches in the target neighborhood. However, the periodic assumption also introduces unwanted boundary effects, which severely degrade the quality of the tracking model.
We propose Spatially Regularized Discriminative Correlation Filters (SRDCF) for tracking. A spatial regularization component is introduced in the learning to penalize correlation filter coefficients depending on their spatial location. Our SRDCF formulation allows the correlation filters to be learned on a significantly larger set of negative training samples, without corrupting the positive samples. We further propose an optimization strategy, based on the iterative Gauss-Seidel method, for efficient online learning of our SRDCF. Experiments are performed on four benchmark datasets: OTB-2013, ALOV++, OTB-2015, and VOT2014. Our approach achieves state-of-the-art results on all four datasets. On OTB-2013 and OTB-2015, we obtain an absolute gain of 8.0% and 8.2% respectively, in mean overlap precision, compared to the best existing trackers."

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">ICCV 2015</b> <b style="font-size:120%;color:#E08040"></b><br> Mitigating the unwanted boundary effects, which limits the performance of correlation based trackers.
tags:
#- Source Themes
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/1608.05571
#url_pdf: 'files/ColoredPointReg_CVPR16.pdf'
url_code: 'https://github.com/martin-danelljan/ECO'
#url_dataset: '#'
url_poster: 'http://www.cvl.isy.liu.se/research/objrec/visualtracking/regvistrack/SRDCF_ICCV15_poster.pdf'
url_project: 'http://www.cvl.isy.liu.se/research/objrec/visualtracking/regvistrack/index.html'
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


