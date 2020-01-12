---
title: "Fragmentation Guided Human Shape Reconstruction"
authors:
- Yingliang Zhang
- <strong>Xi Luo</strong>
- Wei Yang 
- Jingyi Yu
date: "2019-03-01"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Access
publication_short: In *STC*

abstract: We present a novel semantic-driven multi-view reconstruction technique for producing realistic 3D human models. Our approach borrows the fragmentation concept in Cubism style painting where human body is decomposed into semantically meaningful fragments for conveying space and movement. We first employ deep learning based skeleton estimation for warping a proxy human model under the canonical pose to the target multi-view input. It also conducts 3D fragment labeling on the warped  model to separate different human body parts. Finally, we utilize the normal, depth, and fragment label of the proxy model as priors in the multi-view stereo reconstruction process. Comprehensive experiments have shown that our reconstruction technique outperforms the state-of-the-art methods in robustness and accuracy，especially near occlusion boundaries and on textureless regions. In particular, it manages to significantly reduce the "adhesive" artifacts commonly observed in MVS that incorrectly stitches different body parts.

# Summary. An optional shortened abstract.
summary: IEEE Access, 2019

tags: 
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: "publications/ACCESS_2019_fragmentation.pdf"
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---


