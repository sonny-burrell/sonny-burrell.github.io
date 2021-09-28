---
title: "ATOM: Accurate Tracking by Overlap Maximization"
authors:
- admin
- goutam
- Fahad Shahbaz Khan
- Michael Felsberg
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2019-06-25T00:00:00Z"
doi: "10.1109/CVPR.2019.00479"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-06-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer Vision and Pattern Recognition, CVPR 2019*
publication_short: In *CVPR 2019*

abstract: "While recent years have witnessed astonishing improvements in visual tracking robustness, the advancements in tracking accuracy have been limited. As the focus has been directed towards the development of powerful classifiers, the problem of accurate target state estimation has been largely overlooked. In fact, most trackers resort to a simple multi-scale search in order to estimate the target bounding box. We argue that this approach is fundamentally limited since target estimation is a complex task, requiring high-level knowledge about the object.
We address this problem by proposing a novel tracking architecture, consisting of dedicated target estimation and classification components. High level knowledge is incorporated into the target estimation through extensive offline learning. Our target estimation component is trained to predict the overlap between the target object and an estimated bounding box. By carefully integrating target-specific information, our approach achieves previously unseen bounding box accuracy. We further introduce a classification component that is trained online to guarantee high discriminative power in the presence of distractors. Our final tracking framework sets a new state-of-the-art on five challenging benchmarks. On the new large-scale TrackingNet dataset, our tracker ATOM achieves a relative gain of 15% over the previous best approach, while running at over 30 FPS. "

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">CVPR 2019</b> <b style="font-size:120%;color:#E08040">Oral</b><br> Performing accurate bounding box estimation for generic visual tracking. 
tags:
#- Source Themes
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/1811.07628
#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: 'https://github.com/visionml/pytracking#atom'
#url_dataset: '#'
#url_poster: '#'
#url_project: 'https://prunetruong.com/research/gocor'
#url_slides: ''
#url_source: '#'
url_video: 'https://www.youtube.com/watch?v=j7A83F6PRAE&t=3144s'

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


