---
title: "Localizsation and Control for Trajectory Tracking for Autonomous Lawn Mowers"
authors:
- Rico Klinckenberg
date: "2018-09-25T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-08-11T00:00:00Z"

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
- Navigation
- Modelling
featured: true

# links:
# - name: Custom Link
#  url: https://www.scitepress.org/PublicationsDetail.aspx?ID=IpTmQoBTbwc%3d&t=1
url_pdf: https://drive.google.com/file/d/1WS-PMx_IgAv-kE-qWsDnZsftONvEirPK/view?usp=sharing
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
The present bachelor thesis presents the necessary methods for an exact selflocalization by using an Inertial Mesurment Unit (IMU) and the odometry of an
autonomous lawn mower. This self-localization shall be used in later work together
with a localization of a particle filter. The required standard models [12] for the
individual sensor systems were examined and the required parameters determined.
Measurements were taken with the autonomous lawn mower to develop a Kalman
filter [15] based on the data obtained. With the help of the Kalman filter and
a controller which was designed in this thesis, such a self-localization could be
realized. The results show that the autonomous lawnmower can locate itself under
simulated conditions with a higher accuracy than with a pure localization via
odometry. However, final measurements show that disturbances of the IMU occur
within the autonomous lawn mower, so that a final overall behaviour cannot be
implemented with the current architecture of the autonomous lawn mower.
