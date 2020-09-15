---
title: Learning Hierarchical Acquisition Functions for Bayesian Optimization
event: IROS 2020 - Virtual Conference
event_url: https://www.iros2020.org/
location: Las Vegas, USA
summary: A talk about how hierarchical acquisition functions can improve the performance of Bayesian Optimization on complex problems.
abstract: "Learning control policies in robotic tasks requires a large number of interactions due to small learning rates, bounds on the updates or unknown constraints. In contrast humans can infer protective and safe solutions after a single failure or unexpected observation. In order to reach similar performance, we developed a hierarchical Bayesian optimization algorithm that replicates the cognitive inference and memorization process for avoiding failures in motor control tasks. A Gaussian Process implements the modeling and the sampling of the acquisition function. This enables rapid learning with large learning rates while a mental replay phase ensures that policy regions that led to failures are inhibited during the sampling process. The features of the hierarchical Bayesian optimization method are evaluated in a simulated and physiological humanoid postural balancing task. The method outperforms standard optimization techniques, such as Bayesian Optimization, in the number of interactions to solve the task, in the computational demands and in the frequency of observed failures. Further, we show that our method performs similar to humans for learning the postural balancing task by comparing our simulation results with real human data.  \n \n

[Video of the presentation](https://youtu.be/4OkHP1RP9-k), \n
[Corresponding publication](https://nrottmann.github.io/publication/iros2020/)"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2020-10-25T08:00:00Z"
date_end: "2020-10-29T10:00:00Z"
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: "2020-09-15T00:00:00Z"

authors: []
tags:
- Reinforcement Learning
- Optimization
- Humanoids

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image by Nils Rottmann'
  focal_point: Right

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- internal-project

# Enable math on this page?
math: true
---
