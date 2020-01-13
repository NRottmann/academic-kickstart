---
title: "HIBO: Hierarchical Acquisition Functions for Bayesian Optimization"
authors:
- Michael Werner
date: "2019-11-14T00:00:00Z"
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
- Reinforcement Learning
- Optimization
- Humanoid Robotics
featured: true

# links:
# - name: Custom Link
#  url: https://www.scitepress.org/PublicationsDetail.aspx?ID=IpTmQoBTbwc%3d&t=1
url_pdf: https://drive.google.com/file/d/145jsNyEZYfFpcXj9ZNYwC_-NVUdws0v_/view?usp=sharing
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
Bayesian Optimization is a powerful method to optimize black-box derivative-free functions, with high evaluation costs. For instance, applications can be found in the context of robotics, animation design or molecular design. However, Bayesian Optimization is not able to scale into higher dimensions, equivalent to optimizing more than 20 parameters. This thesis introduces HIBO, a new hierarchical algorithm in the context of high dimensional Bayesian Optimization. The algorithm uses an automatic feature generation. The features are used to condition the parameters, to enable faster optimization. The performance of HIBO is compared to existing high dimensional extensions of Bayesian Optimization on three common benchmark functions. Additionally, an air hockey simulation is used to examine the capability in a task-oriented setting. The conducted experiments show that HIBO performs similar to the basic Bayesian Optimization algorithm, independent from the dimensionality of the given problem. Hence, the proposed HIBO algorithm does not scale Bayesian Optimization to higher dimensions.
