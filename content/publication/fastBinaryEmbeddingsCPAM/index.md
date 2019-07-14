+++
title = "Fast binary embeddings, and quantized compressed sensing with structured matrices"
date = 2019-07-2T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Thang Huynh", "Rayan Saab"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "[Communications on Pure and Applied Mathematics](https://onlinelibrary.wiley.com/doi/abs/10.1002/cpa.21850)"
publication_short = "*CPAM*"

# Abstract and optional shortened version.
abstract = "This paper deals with two related problems, namely distance-preserving binary embeddings and quantization for compressed sensing . First, we propose fast methods to replace points from a subset $\\mathcal{X} \\subset \\mathbb{R}^n$, associated with the Euclidean metric, with points in the cube $\\{\\pm 1\\}^m$ and we associate the cube with a pseudo-metric that approximates Euclidean distance among points in $\\mathcal{X}$. Our methods rely on quantizing fast Johnson-Lindenstrauss embeddings based on bounded orthonormal systems and partial circulant ensembles, both of which admit fast transforms. Our quantization methods utilize noise-shaping, and include Sigma-Delta schemes and distributed noise-shaping schemes. The resulting approximation errors decay polynomially and exponentially fast in $m$, depending on the embedding method. This dramatically outperforms the current decay rates associated with binary embeddings and Hamming distances. Additionally, it is the first such binary embedding result that applies to fast Johnson-Lindenstrauss maps while preserving $\\ell_2$ norms. Second, we again consider noise-shaping schemes, albeit this time to quantize compressed sensing measurements arising from bounded orthonormal ensembles and partial circulant matrices. We show that these methods yield a reconstruction error that again decays with the number of measurements (and bits), when using convex optimization for reconstruction. Specifically, for Sigma-Delta schemes, the error decays polynomially in the number of measurements, and it decays exponentially for distributed noise-shaping schemes based on beta encoding. These results are near optimal and the first of their kind dealing with bounded orthonormal systems."
abstract_short = "This paper deals with two related problems, namely distance-preserving binary embeddings and quantization for compressed sensing . First, we propose fast methods to replace points from a subset $\\mathcal{X} \\subset \\mathbb{R}^n$, associated with the Euclidean metric, with points in the cube $\\{\\pm 1\\}^m$ and we associate the cube with a pseudo-metric that approximates Euclidean distance among points in $\\mathcal{X}$. Our methods rely on quantizing fast Johnson-Lindenstrauss embeddings based on bounded orthonormal systems and partial circulant ensembles, both of which admit fast transforms..."

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://arxiv.org/pdf/1801.08639.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  # caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
