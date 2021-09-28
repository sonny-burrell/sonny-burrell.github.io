---
title: "Discriminative Scale Space Tracking"
authors:
- admin
- Gustav Häger
- Fahad Shahbaz Khan
- Michael Felsberg

date: "2014-09-15T00:00:00Z"
doi: "10.1109/TPAMI.2016.2609928"

# Schedule page publish date (NOT publication's date).
publishDate: "2014-09-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Transactions on Pattern Analysis and Machine Intelligence, TPAMI 2017*, and in *British Machine Vision Conference, BMVC 2014.*"
publication_short: In *TPAMI & BMVC 2014*

abstract: "Accurate scale estimation of a target is a challenging research problem in visual object tracking. Most state-of-the-art methods employ an exhaustive scale search to estimate the target size. The exhaustive search strategy is computationally expensive and struggles when encountered with large scale variations. This paper investigates the problem of accurate and robust scale estimation in a tracking-by-detection framework. We propose a novel scale adaptive tracking approach by learning separate discriminative correlation filters for translation and scale estimation. The explicit scale filter is learned online using the target appearance sampled at a set of different scales. Contrary to standard approaches, our method directly learns the appearance change induced by variations in the target scale. Additionally, we investigate strategies to reduce the computational cost of our approach.
Extensive experiments are performed on the OTB and the VOT2014 datasets. Compared to the standard exhaustive scale search, our approach achieves a gain of 2.5% in average overlap precision on the OTB dataset. Additionally, our method is computationally efficient, operating at a 50% higher frame rate compared to the exhaustive scale search. Our method obtains the top rank in performance by outperforming 19 state-of-the-art trackers on OTB and 37 state-of-the-art trackers on VOT2014."

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">TPAMI & BMVC 2014</b> <b style="font-size:120%;color:#E08040"></b><br> Accurate and fast scale estimation for visual tracking.
tags:
#- Source Themes
featured: false

links:
- name: arXiv (journal)
  url: https://arxiv.org/abs/1609.06141
- name: PDF (conf.)
  url: http://www.bmva.org/bmvc/2014/files/paper038.pdf
#url_pdf: 'files/ColoredPointReg_CVPR16.pdf'
url_code: 'https://github.com/martin-danelljan/ECO'
#url_dataset: '#'
#url_poster: 'http://www.cvl.isy.liu.se/research/objrec/visualtracking/regvistrack/SRDCF_ICCV15_poster.pdf'
url_project: 'http://www.cvl.isy.liu.se/research/objrec/visualtracking/scalvistrack/index.html'
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


