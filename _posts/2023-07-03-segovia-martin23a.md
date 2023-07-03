---
title: Double-Weighting for Covariate Shift Adaptation
openreview: WlIJAlWou5
abstract: Supervised learning is often affected by a covariate shift in which the
  marginal distributions of instances (covariates $x$) of training and testing samples
  $p_\text{tr}(x)$ and $p_\text{te}(x)$ are different but the label conditionals coincide.
  Existing approaches address such covariate shift by either using the ratio $p_\text{te}(x)/p_\text{tr}(x)$
  to weight training samples (reweighted methods) or using the ratio $p_\text{tr}(x)/p_\text{te}(x)$
  to weight testing samples (robust methods). However, the performance of such approaches
  can be poor under support mismatch or when the above ratios take large values. We
  propose a minimax risk classification (MRC) approach for covariate shift adaptation
  that avoids such limitations by weighting both training and testing samples. In
  addition, we develop effective techniques that obtain both sets of weights and generalize
  the conventional kernel mean matching method. We provide novel generalization bounds
  for our method that show a significant increase in the effective sample size compared
  with reweighted methods. The proposed method also achieves enhanced classification
  performance in both synthetic and empirical experiments.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: segovia-martin23a
month: 0
tex_title: Double-Weighting for Covariate Shift Adaptation
firstpage: 30439
lastpage: 30457
page: 30439-30457
order: 30439
cycles: false
bibtex_author: Segovia Martin, Jose Ignacio and Mazuelas, Santiago and Liu, Anqi
author:
- given: Jose Ignacio
  family: Segovia Martin
- given: Santiago
  family: Mazuelas
- given: Anqi
  family: Liu
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
pdf: https://proceedings.mlr.press/v202/segovia-martin23a/segovia-martin23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
