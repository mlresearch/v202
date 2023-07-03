---
title: Bayesian Estimation of Differential Privacy
openreview: PwsvGnamYD
abstract: Algorithms such as Differentially Private SGD enable training machine learning
  models with formal privacy guarantees. However, because these guarantees hold with
  respect to unrealistic adversaries, the protection afforded against practical attacks
  is typically much better. An emerging strand of work empirically estimates the protection
  afforded by differentially private training as a confidence interval for the privacy
  budget $\hat{\varepsilon}$ spent with respect to specific threat models. Existing
  approaches derive confidence intervals for $\hat{\varepsilon}$ from confidence intervals
  for false positive and false negative rates of membership inference attacks, which
  requires training an impractically large number of models to get intervals that
  can be acted upon. We propose a novel, more efficient Bayesian approach that brings
  privacy estimates within the reach of practitioners. Our approach reduces sample
  size by computing a posterior for $\hat{\varepsilon}$ (not just a confidence interval)
  from the joint posterior of the false positive and false negative rates of membership
  inference attacks. We implement an end-to-end system for privacy estimation that
  integrates our approach and state-of-the-art membership inference attacks, and evaluate
  it on text and vision classification tasks. For the same number of samples, we see
  a reduction in interval width of up to 40% compared to prior work.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: zanella-beguelin23a
month: 0
tex_title: "{B}ayesian Estimation of Differential Privacy"
firstpage: 40624
lastpage: 40636
page: 40624-40636
order: 40624
cycles: false
bibtex_author: Zanella-Beguelin, Santiago and Wutschitz, Lukas and Tople, Shruti and
  Salem, Ahmed and R\"{u}hle, Victor and Paverd, Andrew and Naseri, Mohammad and K\"{o}pf,
  Boris and Jones, Daniel
author:
- given: Santiago
  family: Zanella-Beguelin
- given: Lukas
  family: Wutschitz
- given: Shruti
  family: Tople
- given: Ahmed
  family: Salem
- given: Victor
  family: Rühle
- given: Andrew
  family: Paverd
- given: Mohammad
  family: Naseri
- given: Boris
  family: Köpf
- given: Daniel
  family: Jones
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
pdf: https://proceedings.mlr.press/v202/zanella-beguelin23a/zanella-beguelin23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
