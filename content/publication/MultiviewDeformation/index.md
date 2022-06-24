---
title: "Multiview Deformation for Dynamic Human Reconstruction"
authors:
- <strong>Xi Luo</strong>
- Yuwei Li
- Wei Yang
- Yu Zhu
- Xin Chen
- YingLiang Zhang
- Shi Jin
- Jingyi Yu
date: "2020-01-10"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract:   We present a novel multi-view dynamic 3D human reconstruction technique based on model based shape deformation. Our approach specifically targets at handling challenging cases such as textureless appearance, heavy occlusions, and depth order ambiguity that are problematic to stereo-based techniques. We propose to pose match and shape deform a human template model to avoid meshing the point cloud. To robustly match the template pose with image observations, we present a novel Graph Convolutional Networks (GCN) to gradually filter out erroneous views and use the optimal subset for recovering the 3D skeleton and warping the template shape. Next, We use the warped human template to guide the cross-view consistent semantic segmentation. We set out to deform the warped 3D model so that the silhouette of the deformed model best matches the target in respective views while maintaining semantic consistency. Comprehensive experiments on publicly available and our newly generated complex motion datasets show our approach significantly outperforms the state-of-the-art on sparse cameras, textureless regions (e.g., under black clothing), complex motions, etc.

# Summary. An optional shortened abstract.
summary: \[Arxiv]

tags:
featured: true

links:
# - name: Talk
#   url: "https://www.youtube.com/watch?v=DL6duxO1-6w"
# url_pdf: "publications/SweepCanvas_Sketch-based_3D_Prototyping_on_an_RGBD.pdf"
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: "https://www.youtube.com/watch?v=Xnp3_eMYXj0"

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
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
