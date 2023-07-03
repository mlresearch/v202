---
title: Random Grid Neural Processes for Parametric Partial Differential Equations
openreview: g6WlWFFZxa
abstract: We introduce a new class of spatially stochastic physics and data informed
  deep latent models for parametric partial differential equations (PDEs) which operate
  through scalable variational neural processes. We achieve this by assigning probability
  measures to the spatial domain, which allows us to treat collocation grids probabilistically
  as random variables to be marginalised out. Adapting this spatial statistics view,
  we solve forward and inverse problems for parametric PDEs in a way that leads to
  the construction of Gaussian process models of solution fields. The implementation
  of these random grids poses a unique set of challenges for inverse physics informed
  deep learning frameworks and we propose a new architecture called Grid Invariant
  Convolutional Networks (GICNets) to overcome these challenges. We further show how
  to incorporate noisy data in a principled manner into our physics informed model
  to improve predictions for problems where data may be available but whose measurement
  location does not coincide with any fixed mesh or grid. The proposed method is tested
  on a nonlinear Poisson problem, Burgers equation, and Navier-Stokes equations, and
  we provide extensive numerical comparisons. We demonstrate significant computational
  advantages over current physics informed neural learning methods for parametric
  PDEs while improving the predictive capabilities and flexibility of these models.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: vadeboncoeur23a
month: 0
tex_title: Random Grid Neural Processes for Parametric Partial Differential Equations
firstpage: 34759
lastpage: 34778
page: 34759-34778
order: 34759
cycles: false
bibtex_author: Vadeboncoeur, Arnaud and Kazlauskaite, Ieva and Papandreou, Yanni and
  Cirak, Fehmi and Girolami, Mark and Akyildiz, Omer Deniz
author:
- given: Arnaud
  family: Vadeboncoeur
- given: Ieva
  family: Kazlauskaite
- given: Yanni
  family: Papandreou
- given: Fehmi
  family: Cirak
- given: Mark
  family: Girolami
- given: Omer Deniz
  family: Akyildiz
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
pdf: https://proceedings.mlr.press/v202/vadeboncoeur23a/vadeboncoeur23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
