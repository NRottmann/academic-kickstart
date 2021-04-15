---
title: "Learning Motion Models for Local Path Planning Strategies"
authors:
- Leander Busch
date: "2021-02-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-02-15T00:00:00Z"

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
- Mobile Robotics
- Planning
- Machine Learning

featured: true

# links:
# - name: Custom Link
#  url: https://www.scitepress.org/PublicationsDetail.aspx?ID=IpTmQoBTbwc%3d&t=1
url_pdf: https://ai-lab.science/wp/theses/Busch_BscThesis_2021.pdf
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
The Segway Loomo is a self-balancing segway robot, which is constantly balanced
by an internal control system. A local path planning strategy was developed in
advance for this robot. For local path planning, a motion model of the robot
is needed to determine the effect of velocity commands on the robot’s pose. In
the implemented local path planner, a simple motion model of the robot is used,
which does not model the effect of the segway robot’s internal control on its
motion. In this work, it was investigated whether a more accurate motion model
for the Segway Loomo robot can be learned by using artificial neural networks
to improve the local path planning for this robot. For this purpose, different
architectures of feedforward networks were tested. The neural networks were
trained and evaluated using recorded motion data of the segway robot. The
best learned model was validated by using a standard differential drive motion
model as a reference. For the validation of the learned model, the accuracy of
both motion models was examined on the recorded motion data. On average,
the learned model is 59.48 % more accurate in determining the position of the
robot at the next time step and 24.61 % more accurate in determining the new
orientation of the robot than the differential drive motion model.
