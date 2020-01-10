---
title: "Towards 3D Human Shape Recovery Under Clothing"
authors:
- Chen Xin
- Pang Anqi  
- Zhu Yu  
- Li Yuwei  
- <strong>Luo Xi</strong>
- Zhang Ge  
- Wang Peihao  
- Zhang Yingliang  
- Li Shiying  
- Yu Jingyi
date: "2019-06-01"
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

abstract: We present a learning-based scheme for robustly and accurately estimating clothing fitness as well as the human shape on clothed 3D human scans. Our approach maps the clothed human geometry to a geometry image that we call clothed-GI. To align clothed-GI under different clothing, we extend the parametric human model and employ skeleton detection and warping for reliable alignment. For each pixel on the clothed-GI, we extract a feature vector including color/texture, position, normal, etc. and train a modified conditional GAN network for per-pixel fitness prediction using a comprehensive 3D clothing. Our technique significantly improves the accuracy of human shape prediction, especially under loose and fitted clothing. We further demonstrate using our results for human/clothing segmentation and virtual clothes fitting at a high visual realism.


# Summary. An optional shortened abstract.
summary: Arxiv 2019

tags:
featured: false

links:
# - name: Talk
#   url: "https://www.youtube.com/watch?v=DL6duxO1-6w"
url_pdf: "publications/FitnessPrediction_arxiv2019_paper.pdf"
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: "https://www.youtube.com/watch?v=Xnp3_eMYXj0"

# Featured image
# To use add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise set `slides: ""`.
slides: example
---
