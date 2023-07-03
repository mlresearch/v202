---
title: Cold Analysis of Rao-Blackwellized Straight-Through Gumbel-Softmax Gradient
  Estimator
openreview: 9GjM8UzCYN
abstract: Many problems in machine learning require an estimate of the gradient of
  an expectation in discrete random variables with respect to the sampling distribution.
  This work is motivated by the development of the Gumbel-Softmax family of estimators,
  which use a temperature-controlled relaxation of discrete variables. The state-of-the
  art in this family, the Gumbel-Rao estimator uses an extra internal sampling to
  reduce the variance, which may be costly. We analyze this estimator and show that
  it possesses a zero temperature limit with a surprisingly simple closed form. The
  limit estimator, called ZGR, has favorable bias and variance properties, it is easy
  to implement and computationally inexpensive. It decomposes as the average of the
  straight through (ST) estimator and DARN estimator — two basic but not very well
  performing on their own estimators. We demonstrate that the simple ST–ZGR family
  of estimators practically dominates in the bias-variance tradeoffs the whole GR
  family while also outperforming SOTA unbiased estimators.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: shekhovtsov23a
month: 0
tex_title: Cold Analysis of Rao-Blackwellized Straight-Through {G}umbel-Softmax Gradient
  Estimator
firstpage: 30931
lastpage: 30955
page: 30931-30955
order: 30931
cycles: false
bibtex_author: Shekhovtsov, Alexander
author:
- given: Alexander
  family: Shekhovtsov
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
pdf: https://proceedings.mlr.press/v202/shekhovtsov23a/shekhovtsov23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
