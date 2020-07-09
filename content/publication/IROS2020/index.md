---
title: "Learning Hierarchical Acquisition Functions for Bayesian Optimization"
authors:
- admin
- Tjasa Kunavar
- Jan Babic
- Jan Peters
- Elmar Rueckert
date: "2020-10-25T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-05-22T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IROS*
# publication_short: In *STC*

abstract: "Learning control policies in robotic tasks requires a large number of interactions due to small learning rates, bounds on the updates or unknown constraints. In contrast humans can infer protective and safe solutions after a single failure or unexpected observation. In order to reach similar performance, we developed a hierarchical Bayesian optimization algorithm that replicates the cognitive inference and memorization process for avoiding failures in motor control tasks. A Gaussian Process implements the modeling and the sampling of the acquisition function. This enables rapid learning with large learning rates while a mental replay phase ensures that policy regions that led to failures are inhibited during the sampling process. The features of the hierarchical Bayesian optimization method are evaluated in a simulated and physiological humanoid postural balancing task. The method outperforms standard optimization techniques, such as Bayesian Optimization, in the number of interactions to solve the task, in the computational demands and in the frequency of observed failures. Further, we show that our method performs similar to humans for learning the postural balancing task by comparing our simulation results with real human data."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Reinforcement Learning
- Optimization
- Humanoids
featured: true

# links:
# - name: Custom Link
#  url: https://www.scitepress.org/PublicationsDetail.aspx?ID=IpTmQoBTbwc%3d&t=1
url_pdf: https://rob.ai-lab.science/wp/IROS2020Rottmann.pdf
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
  caption: 'HiBO Diagram'
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
