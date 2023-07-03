---
title: Adaptive Annealed Importance Sampling with Constant Rate Progress
openreview: x0AppdesIM
abstract: Annealed Importance Sampling (AIS) synthesizes weighted samples from an
  intractable distribution given its unnormalized density function. This algorithm
  relies on a sequence of interpolating distributions bridging the target to an initial
  tractable distribution such as the well-known geometric mean path of unnormalized
  distributions which is assumed to be suboptimal in general. In this paper, we prove
  that the geometric annealing corresponds to the distribution path that minimizes
  the KL divergence between the current particle distribution and the desired target
  when the feasible change in the particle distribution is constrained. Following
  this observation, we derive the constant rate discretization schedule for this annealing
  sequence, which adjusts the schedule to the difficulty of moving samples between
  the initial and the target distributions. We further extend our results to $f$-divergences
  and present the respective dynamics of annealing sequences based on which we propose
  the Constant Rate AIS (CR-AIS) algorithm and its efficient implementation for $\alpha$-divergences.
  We empirically show that CR-AIS performs well on multiple benchmark distributions
  while avoiding the computationally expensive tuning loop in existing Adaptive AIS.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: goshtasbpour23a
month: 0
tex_title: Adaptive Annealed Importance Sampling with Constant Rate Progress
firstpage: 11642
lastpage: 11658
page: 11642-11658
order: 11642
cycles: false
bibtex_author: Goshtasbpour, Shirin and Cohen, Victor and Perez-Cruz, Fernando
author:
- given: Shirin
  family: Goshtasbpour
- given: Victor
  family: Cohen
- given: Fernando
  family: Perez-Cruz
date: 2023-07-03
address: 
container-title: Proceedings of the 40th International Conference on Machine Learning
volume: '202'
genre: inproceedings
issued:
  date-parts:
  - 2023
  - 7
  - 3
pdf: https://proceedings.mlr.press/v202/goshtasbpour23a/goshtasbpour23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
