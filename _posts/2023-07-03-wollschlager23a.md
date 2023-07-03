---
title: 'Uncertainty Estimation for Molecules: Desiderata and Methods'
openreview: DjwMRloMCO
abstract: Graph Neural Networks (GNNs) are promising surrogates for quantum mechanical
  calculations as they establish unprecedented low errors on collections of molecular
  dynamics (MD) trajectories. Thanks to their fast inference times they promise to
  accelerate computational chemistry applications. Unfortunately, despite low in-distribution
  (ID) errors, such GNNs might be horribly wrong for out-of-distribution (OOD) samples.
  Uncertainty estimation (UE) may aid in such situations by communicating the model’s
  certainty about its prediction. Here, we take a closer look at the problem and identify
  six key desiderata for UE in molecular force fields, three ’physics-informed’ and
  three ’application-focused’ ones. To overview the field, we survey existing methods
  from the field of UE and analyze how they fit to the set desiderata. By our analysis,
  we conclude that none of the previous works satisfies all criteria. To fill this
  gap, we propose Localized Neural Kernel (LNK) a Gaussian Process (GP)-based extension
  to existing GNNs satisfying the desiderata. In our extensive experimental evaluation,
  we test four different UE with three different backbones across two datasets. In
  out-of-equilibrium detection, we find LNK yielding up to 2.5 and 2.1 times lower
  errors in terms of AUC-ROC score than dropout or evidential regression-based methods
  while maintaining high predictive performance.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: wollschlager23a
month: 0
tex_title: 'Uncertainty Estimation for Molecules: Desiderata and Methods'
firstpage: 37133
lastpage: 37156
page: 37133-37156
order: 37133
cycles: false
bibtex_author: Wollschl\"{a}ger, Tom and Gao, Nicholas and Charpentier, Bertrand and
  Ketata, Mohamed Amine and G\"{u}nnemann, Stephan
author:
- given: Tom
  family: Wollschläger
- given: Nicholas
  family: Gao
- given: Bertrand
  family: Charpentier
- given: Mohamed Amine
  family: Ketata
- given: Stephan
  family: Günnemann
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
pdf: https://proceedings.mlr.press/v202/wollschlager23a/wollschlager23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
