---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Green Simulation Assisted Reinforcement Learning with Model Risk for Biomanufacturing
  Learning and Control
subtitle: ''
summary: ''
authors:
- Hua Zheng
- Wei Xie
- M. Ben Feng
tags: []
categories: []
date: '2020-01-01'
lastmod: 2021-06-13T20:49:52-04:00
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
publishDate: '2021-06-14T00:49:51.969067Z'
publication_types:
- '1'
abstract: Biopharmaceutical manufacturing faces critical challenges, including complexity,
  high variability, lengthy lead time, and limited historical data and knowledge of
  the underlying system stochastic process. To address these challenges, we propose
  a green simulation assisted model-based reinforcement learning to support process
  online learning and guide dynamic decision making. Basically, the process model
  risk is quantified by the posterior distribution. At any given policy, we predict
  the expected system response with prediction risk accounting for both inherent stochastic
  uncertainty and model risk. Then, we propose green simulation assisted reinforcement
  learning and derive the mixture proposal distribution of decision process and likelihood
  ratio based metamodel for the policy gradient, which can selectively reuse process
  trajectory outputs collected from previous experiments to increase the simulation
  data-efficiency, improve the policy gradient estimation accuracy, and speed up the
  search for the optimal policy. Our numerical study indicates that the proposed approach
  demonstrates the promising performance.
publication: '*Proceedings of the Winter Simulation Conference*'
url_code: https://github.com/zhenghuazx/BayesianLRPolicySearch
url_pdf: https://informs-sim.org/wsc20papers/028.pdf
---
