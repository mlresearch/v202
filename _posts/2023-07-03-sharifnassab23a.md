---
title: Toward Efficient Gradient-Based Value Estimation
openreview: hGI6SjQ7Ty
abstract: Gradient-based methods for value estimation in reinforcement learning have
  favorable stability properties, but they are typically much slower than Temporal
  Difference (TD) learning methods. We study the root causes of this slowness and
  show that Mean Square Bellman Error (MSBE) is an ill-conditioned loss function in
  the sense that its Hessian has large condition-number. To resolve the adverse effect
  of poor conditioning of MSBE on gradient based methods, we propose a low complexity
  batch-free proximal method that approximately follows the Gauss-Newton direction
  and is asymptotically robust to parameterization. Our main algorithm, called RANS,
  is efficient in the sense that it is significantly faster than the residual gradient
  methods while having almost the same computational complexity, and is competitive
  with TD on the classic problems that we tested.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sharifnassab23a
month: 0
tex_title: Toward Efficient Gradient-Based Value Estimation
firstpage: 30827
lastpage: 30849
page: 30827-30849
order: 30827
cycles: false
bibtex_author: Sharifnassab, Arsalan and Sutton, Richard S.
author:
- given: Arsalan
  family: Sharifnassab
- given: Richard S.
  family: Sutton
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
pdf: https://proceedings.mlr.press/v202/sharifnassab23a/sharifnassab23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
