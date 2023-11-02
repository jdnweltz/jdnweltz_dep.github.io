---
title: Reinforcement Learning Respondent Driven Sampling
summary: Respondent Driven Sampling (RDS) is widely used to access populations that are difficult to reach through conventional sampling mechanisms by incentivizing study participants to recruit their social connections. We consider adapting this inherent incentive structure to maximize cumulative goals during the study using reinforcement learning. However, the relationship between sample participants resulting from the social network structure poses unique challenges for solving this problem. To address this dependence, we use a branching process as a working model for reinforcement learning RDS (RLRDS). Establishing the conditions for asymptotic normality of the maximum likelihood estimator under this model allows us to perform reinforcement learning and inference with favorable theoretical guarantees. We establish asymptotic regret bounds for Thompson sampling, which balances exploration and exploitation when approximating the optimal allocation strategy. After collecting the sample using RLRDS, we perform inference for functions of population characteristics under an arbitrary generative social network model using an approximate Wald interval approach. Lastly, we demonstrate the utility of RLRDS and the accuracy of our inferential approach in simulation studies.
tags:
  - Network Sampling
  - Reinforcement Learning
date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:
---