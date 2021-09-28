---
title: "Beyond Correlation Filters: Learning Continuous Convolution Operators for Visual Tracking"
authors:
- admin
- Andreas Robinson
- Fahad Shahbaz Khan
- Michael Felsberg

date: "2016-10-05T00:00:00Z"
doi: "10.1007/978-3-319-46454-1\_29"

# Schedule page publish date (NOT publication's date).
publishDate: "2016-10-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *European Conference on Computer Vision, ECCV 2016*
publication_short: In *ECCV 2016*

abstract: "Discriminative Correlation Filters (DCF) have demonstrated excellent performance for visual object tracking. The key to their success is the ability to efficiently exploit available negative data by including all shifted versions of a training sample. However, the underlying DCF formulation is restricted to single-resolution feature maps, significantly limiting its potential. In this paper, we go beyond the conventional DCF framework and introduce a novel formulation for training continuous convolution filters. We employ an implicit interpolation model to pose the learning problem in the continuous spatial domain. Our proposed formulation enables efficient integration of multi-resolution deep feature maps, leading to superior results on three object tracking benchmarks: OTB-2015 (+5.1% in mean OP), Temple-Color (+4.6% in mean OP), and VOT2015 (20% relative reduction in failure rate). Additionally, our approach is capable of sub-pixel localization, crucial for the task of accurate feature point tracking. We also demonstrate the effectiveness of our learning formulation in extensive feature point tracking experiments."

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">ECCV 2016</b> <b style="font-size:120%;color:#E08040">Oral</b><br> A theoretical framework for discriminatively learning a convolution operator in the continuous spatial domain.
tags:
#- Source Themes
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/1608.03773
- name: Supplementary
  url: files/C-COT_ECCV16_suppl.pdf
- name: Code (Unofficial Python)
  url: https://github.com/visionml/pytracking#eco
#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: 'https://github.com/martin-danelljan/Continuous-ConvOp'
#url_dataset: '#'
url_poster: 'http://www.cvl.isy.liu.se/research/objrec/visualtracking/conttrack/C-COT_ECCV16_poster.pdf'
#url_project: 'https://prunetruong.com/research/gocor'
url_slides: 'http://www.cvl.isy.liu.se/research/objrec/visualtracking/conttrack/C-COT_VOT16_slides.pdf'
#url_source: '#'
url_video: 'http://videolectures.net/eccv2016_danelljan_visual_tracking/'

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


