+++
title = "DeepRF: Ultrafast population receptive field mapping with deep learning"
date = 2019-08-14T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["J Thielen", "U Güçlü", "Y Güçlütürk", "L Ambrogioni", "__SE Bosch__", "MAJ van Gerven"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Preprint / Working Paper
# 4 = Report
# 5 = Book
# 6 = Book section
# 7 = Thesis
# 8 = Patent
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = "_bioRxiv_"
publication_short = ""

# Abstract and optional shortened version.
abstract = "Population receptive field (pRF) mapping is an important asset for cognitive neuroscience. The pRF model is used for estimating retinotopy, defining functional localizers and to study a vast amount of cognitive tasks. In a classic pRF, the cartesian location and receptive field size are modeled as a 2D Gaussian kernel in visual space and are estimated by optimizing the fit between observed responses and predicted responses. In the standard framework this is achieved using an iterative gradient descent algorithm. This optimization is time consuming because the number of pRFs to fit (e.g., fMRI voxels) is typically large. This computation time increases further with the complexity of the pRF model (e.g., adding HRF parameters, surround suppression and uncertainty measures). Here, we introduce DeepRF, which uses deep convolutional neural networks to estimate pRFs. We compare the performance of DeepRF with that of the conventional method using a synthetic dataset for which the ground truth is known and an empirical dataset. We show that DeepRF achieves state-of-the-art performance while being more than 3 orders of magnitude faster than the conventional method. This enables easier and faster modeling of more complex pRF models, resolving an important limitation of the conventional approach."
abstract_short = ""

# Is this a featured publication? (true/false)
featured = false

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
tags = ["fMRI", "visual perception", "population receptive field mapping", "artificial neural networks"]

# Links (optional).
url_pdf = "/files/2019_thielen_biorxiv.pdf"
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
doi = "10.1101/732990"

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  #caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "TopRight"
+++
