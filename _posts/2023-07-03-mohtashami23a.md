---
title: Special Properties of Gradient Descent with Large Learning Rates
openreview: DGSmVHmOrv
abstract: When training neural networks, it has been widely observed that a large
  step size is essential in stochastic gradient descent (SGD) for obtaining superior
  models. However, the effect of large step sizes on the success of SGD is not well
  understood theoretically. Several previous works have attributed this success to
  the stochastic noise present in SGD. However, we show through a novel set of experiments
  that the stochastic noise is not sufficient to explain good non-convex training,
  and that instead the effect of a large learning rate itself is essential for obtaining
  best performance.We demonstrate the same effects also in the noise-less case, i.e.
  for full-batch GD. We formally prove that GD with large step size —on certain non-convex
  function classes — follows a different trajectory than GD with a small step size,
  which can lead to convergence to a global minimum instead of a local one. Our settings
  provide a framework for future analysis which allows comparing algorithms based
  on behaviors that can not be observed in the traditional settings.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mohtashami23a
month: 0
tex_title: Special Properties of Gradient Descent with Large Learning Rates
firstpage: 25082
lastpage: 25104
page: 25082-25104
order: 25082
cycles: false
bibtex_author: Mohtashami, Amirkeivan and Jaggi, Martin and Stich, Sebastian U
author:
- given: Amirkeivan
  family: Mohtashami
- given: Martin
  family: Jaggi
- given: Sebastian U
  family: Stich
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
pdf: https://proceedings.mlr.press/v202/mohtashami23a/mohtashami23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
