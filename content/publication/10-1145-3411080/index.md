---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Global-Local Metamodel-Assisted Stochastic Programming via Simulation
subtitle: ''
summary: ''
authors:
- Wei Xie
- Yuan Yi
- Hua Zheng
tags:
- '"dynamic decision-making"'
- '"two-stage optimization"'
- '"Simulation optimization"'
- '"stochastic programming"'
- '"Gaussian process metamodel"'
categories: []
date: '2021-12-01'
lastmod: 2021-06-13T20:56:24-04:00
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
publishDate: '2021-06-14T00:56:23.815267Z'
publication_types:
- '2'
abstract: 'To integrate strategic, tactical, and operational decisions, stochastic
  programming has been widely used to guide dynamic decision-making. In this article,
  we consider complex systems and introduce the global-local metamodel-assisted stochastic
  programming via simulation that can efficiently employ the simulation resource to
  iteratively solve for the optimal first- and second-stage decisions. Specifically,
  at each visited first-stage decision, we develop a local metamodel to simultaneously
  solve a set of scenario-based second-stage optimization problems, which also allows
  us to estimate the optimality gap. Then, we construct a global metamodel accounting
  for the errors induced by: (1) using a finite number of scenarios to approximate
  the expected future cost occurring in the planning horizon, (2) second-stage optimality
  gap, and (3) finite visited first-stage decisions. Assisted by the global-local
  metamodel, we propose a new simulation optimization approach that can efficiently
  and iteratively search for the optimal first- and second-stage decisions. Our framework
  can guarantee the convergence of optimal solution for the discrete two-stage optimization
  with unknown objective, and the empirical study indicates that it achieves substantial
  efficiency and accuracy.'
publication: '*ACM Trans. Model. Comput. Simul.*'
url_pdf: https://doi.org/10.1145/3411080
doi: 10.1145/3411080
---
