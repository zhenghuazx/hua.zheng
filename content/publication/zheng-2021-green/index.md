---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Green Simulation Assisted Policy Gradient to Accelerate Stochastic Process
  Control
subtitle: ''
summary: 'This study is motivated by the critical challenges in the biopharmaceutical manufacturing, including high complexity, high uncertainty, and very limited process data. Each experiment run is often very expensive. To support the optimal and robust process control, we propose a general green simulation assisted policy gradient (GS-PG) framework for both online and offline learning settings. Basically, to address the key limitations of state-of-art reinforcement learning (RL), such as sample inefficiency and low reliability, we create a mixture likelihood ratio based policy gradient estimation that can leverage on the information from historical experiments conducted under different inputs, including process model coefficients and decision policy parameters. Then, to accelerate the learning of optimal and robust policy, we further propose a variance reduction based sample selection method that allows GS-PG to intelligently select and reuse most relevant historical trajectories. The selection rule automatically updates the samples to be reused during the learning of process mechanisms and the search for optimal policy. Our theoretical and empirical studies demonstrate that the proposed framework can perform better than the state-of-art policy gradient approach and accelerate the optimal robust process control for complex stochastic systems under high uncertainty. '
authors:
- Hua Zheng
- Wei Xie
- M Ben Feng
tags: []
categories: []
date: '2021-10-26'
lastmod: 2021-10-26T12:30:15-04:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-10-26T16:30:15.537584Z'
publication_types:
- '2'
abstract: ''
publication: '*arXiv preprint arXiv:2110.08902*'
url_pdf: https://arxiv.org/pdf/2110.08902.pdf
---
