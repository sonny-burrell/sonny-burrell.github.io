---
title: "Learning the Model Update for Siamese Trackers"
authors:
- Lichao Zhang
- Abel Gonzalez-Garcia
- Joost van de Weijer
- admin
- Fahad Shahbaz Khan

date: "2019-11-09T00:00:00Z"
doi: "10.1109/ICCV.2019.00411"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-11-09T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Computer Vision, ICCV 2019*
publication_short: In *ICCV 2019*

abstract: "Siamese approaches address the visual tracking problem by extracting an appearance template from the current frame, which is used to localize the target in the next frame. In general, this template is linearly combined with the accumulated template from the previous frame, resulting in an exponential decay of information over time. While such an approach to updating has led to improved results, its simplicity limits the potential gain likely to be obtained by learning to update. Therefore, we propose to replace the handcrafted update function with a method which learns to update. We use a convolutional neural network, called UpdateNet, which given the initial template, the accumulated template and the template of the current frame aims to estimate the optimal template for the next frame. The UpdateNet is compact and can easily be integrated into existing Siamese trackers. We demonstrate the generality of the proposed approach by applying it to two Siamese trackers, SiamFC and DaSiamRPN. Extensive experiments on VOT2016, VOT2018, LaSOT, and TrackingNet datasets demonstrate that our UpdateNet effectively predicts the new target template, outperforming the standard linear update. On the large-scale TrackingNet dataset, our UpdateNet improves the results of DaSiamRPN with an absolute gain of 3.9% in terms of success score."

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">ICCV 2019</b> <b style="font-size:120%;color:#E08040"></b><br> Replacing the handcrafted update function in Siamese trackers with a learnable update mechanism. 
tags:
#- Source Themes
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/1908.00855
#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: 'https://github.com/zhanglichao/updatenet'
#url_dataset: '#'
#url_poster: '#'
#url_project: 'https://prunetruong.com/research/gocor'
#url_slides: ''
#url_source: '#'
#url_video: 'https://www.youtube.com/watch?v=ozblfyuemrw&ab_channel=VisionML'

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


