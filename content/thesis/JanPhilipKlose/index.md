---
title: "Plant Classification based on Chlorophyll Detection for autonomous Gardening"
authors:
- Jan-Philip Klose
date: "2020-08-27T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-08-27T00:00:00Z"

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
url_pdf: https://drive.google.com/file/d/1Bg_7qwJgGry4A8-ZYcaSoZbTYIz1MrEi/view?usp=sharing
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
Upon illumination of a sufficient amount of light, the chlorophyll molecules of
a plant start to emit photons in the far red region of the light spectrum. This
phenomenon is also known as chlorophyll fluorescence. In this thesis a classi-
fier is built that serves as a benchmark for plant classification via chlorophyll a
fluorescence. A data set of 2500 samples was acquired by illuminating a total
of 500 leaves gathered from five different plants with seven LEDs. To achieve
an optimal model, a convolutional neural network (CNN) was designed and
trained on complete fluorescence spectra. The network achieved an average
accuracy of 95,7% on classifying five plants. Furthermore, the networks ac-
curacy on a smaller set of LEDs was tested. In the end, a low cost approach
was trained and evaluated, reaching an accuracy of 68%. This approach uses
simulated phototransistor data instead of full spectra acquired with a spec-
trometer.
