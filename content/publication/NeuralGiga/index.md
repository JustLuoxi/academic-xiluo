---
title: "NeuralGiga: Neural Giga-Image Representation with Anti-aliasing and
Continuous Viewing"
authors:
- <strong>Xi Luo</strong>
- Yuwei Li
- Minye Wu
- Yuexin Ma
- Lan Xu
- Jingyi Yu
date: "2022-05-04"
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

abstract:   A gigapixel image consists of billions of pixels with color information to record fine details of the scene, leading to tremendous data overload for storage and display. Recent advances of gigapixel imaging still suffer from large storage size, I/O overhead
or spatial aliasing for achieving real-time rendering especially during zoom-in or zoom-out. To fill this gap, in this paper, we
propose NeuralGiga, a novel neural representation of gigapixel images with an effective neural rendering scheme. NeuralGiga
implicitly encodes the entire image into a light-weight network which maps pixel coordinates into RGB values with efficient
storage overload. In our novel neural rendering network, to enable high-quality giga-image regression with anti-aliasing and
continuous viewing effect, we introduce a Spectrum Multi-Layer Perceptron (MLP) design and a Gaussian-based Integrated
Random Fourier Feature Mapping (GIRFFM) scheme. In our Spectrum MLP, we adopt a hierarchical network architecture to
explicitly disentangle the high-frequency and low-frequency signals in the implicit representation framework, so as to boost the
regression quality of detailed giga-level textures and reduce computational and storage complexity significantly. Such spectrum
design even enables real-time gigapixel image rendering under lower zoom levels. In our GIRFFM scheme, we adopt the
Random Fourier Feature Mapping to project pixel coordinates into a novel feature space to facilitate high-frequency signal
learning. Besides, we embed our GIRFFM into a multi-scale training framework for continuous pixel cone integration in
a single pass, which enables spatial anti-aliasing in the task of gigapixel image display. Extensive experiments on various
scenarios illustrate the effectiveness of our approach to achieve high-quality neural giga-image representation for both storage
and display.

# Summary. An optional shortened abstract.
summary: \[In submission]

tags:
featured: true

links:
#- name: Talk
#  url: "https://www.youtube.com/watch?v=DL6duxO1-6w"
# url_pdf: ""
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: "https://www.youtube.com/watch?v=Xnp3_eMYXj0"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: ''
#   focal_point: ""
#   preview_only: false

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
