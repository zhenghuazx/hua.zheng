---
title: Green Simulation Assisted Reinforcement Learning Presentation in WSC 2020

event: Winter Simulation Conference 2020
event_url: http://meetings2.informs.org/wordpress/wsc2020/

location: Virtual
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: Green Simulation Assisted Reinforcement Learning with Model Risk for Biomanufacturing Learning and Control.
abstract: "Biopharmaceutical manufacturing faces critical challenges, including complexity, high variability, lengthy lead time, and limited historical data and domain knowledge of the underlying system stochastic process. To address these challenges, we propose a green simulation assisted model-based reinforcement learning (GS-RL) method where the bioprocess model risk is quantified by the posterior distribution given observed data and all simulation outputs in the learning process are being efficiently recycled and reused. The main benefit of the proposed method is high computational efficiency, as it simultaneously guides learning and dynamic decision making. The green simulation likelihood ratio metamodel reuses simulation outputs from previous iterations in a stochastic search algorithm for the optimal policy and the outputs from previous experiments. As such, the quality of gradient estimation is improved and the search for the optimal policy converges faster. Our numerical studies show promising results."


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2020-12-15T10:30:00Z"
date_end: "2020-12-15T11:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Right

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/HuaZhen96028186
url_code: "https://github.com/zhenghuazx/BayesianLRPolicySearch"
url_pdf: "https://informs-sim.org/wsc20papers/028.pdf"
url_slides: "https://github.com/zhenghuazx/BayesianLRPolicySearch/blob/master/WSC2020_GreenSimulationPolicyGradient-final.pdf"
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
# - example
---