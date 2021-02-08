---
title: "Machine Learning for plant classification based on chlorophyll detection"
authors:
- Alexander Walter
date: "2019-06-17T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-06-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: University of Luebeck
# publication_short: In *STC*

abstract: ""

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Sensors
- Optimization
- Machine Learning

featured: true

# links:
# - name: Custom Link
#  url: https://www.scitepress.org/PublicationsDetail.aspx?ID=IpTmQoBTbwc%3d&t=1
url_pdf: https://drive.google.com/file/d/1a_R0NLwQYCPeFQePiV3GMlGIMegdgOb-/view?usp=sharing
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
## Abstract
Based on the intention to build an autonomous lawn mower robot, this work
examines the viability of a sensor and microprocessor for onboard plant clas-
sification using machine learning. Usually, some sort of fencing is required to
keep the robot in its intended processing area, so such a sensor would allow
the robot to differentiate between grass and e.g. flowers. Also, the drive and
blade speed can be adjusted for certain species or plant densities, etc.
For this, a data set was collected utilizing a specific method called chloro-
phyll fluorescence induction. A series of narrowband LEDs are used to drive
this process, while a spectrometer measures the spectral intensity. The plant
will fluoresce in specific wavelengths when sufficiantly illuminated. With this
data, machine learning algorithms are trained to explore if they are capable
to classify these plants without further information.
With accuracies up to 98% for three plants commonly present on a lawn
and up to 86% for eight plants, the results show that chlorophyll fluorescence
is a viable method for classification, even under sunlight using the random
forest machine learning algorithm.
