---
title: "Loop Closure Detection in Closed Environments"
authors:
- admin
- Ralf Bruder
- Achim Schweikard
- Elmar Rueckert
date: "2019-09-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-08-29T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ECMR*
# publication_short: In *STC*

abstract: "Low cost robots, such as vacuum cleaners or lawn mowers employ simplistic and often random navigation policies. Although a large number of sophisticated mapping and planning approaches exist, they require additional sensors like LIDAR sensors, cameras or time of flight sensors. In this work, we propose a loop closure detection method based only on odometry data which can be generated using low-range or binary signal sensors together with simple wall following techniques. We show how to include the detected loop closing constraints into a pose graph formulation such that standard pose graph optimization techniques can be used for map estimation.
We evaluate our map estimate and loop closure approach using both, simulation and a real lawn mower in complex and realistic environments. Our results demonstrate that our approach generates accurate map estimates on the basis of odometry data only. We further show that our assumption about the discriminative nature of neighboring poses in the pose graph is solid, even under large odometry noise. These improved map estimates provide the basis for smart navigation policies in low cost robots and extends their abilities to goal-directed behavior like pick and place or complete coverage path planning in realistic environments. "

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Mobile Robotics
- Mapping
- SLAM
featured: true

# links:
# - name: Custom Link
#  url: https://www.scitepress.org/PublicationsDetail.aspx?ID=IpTmQoBTbwc%3d&t=1
url_pdf: https://arxiv.org/abs/1908.04564
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
  caption: "Mapping of an Apartment."
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
