---
title: 'Nonlinear Advantage: Trained Networks Might Not Be As Complex as You Think'
openreview: tAa6ivLs6D
abstract: We perform an empirical study of the behaviour of deep networks when fully
  linearizing some of its feature channels through a sparsity prior on the overall
  number of nonlinear units in the network. In experiments on image classification
  and machine translation tasks, we investigate how much we can simplify the network
  function towards linearity before performance collapses. First, we observe a significant
  performance gap when reducing nonlinearity in the network function early on as opposed
  to late in training, in-line with recent observations on the time-evolution of the
  data-dependent NTK. Second, we find that after training, we are able to linearize
  a significant number of nonlinear units while maintaining a high performance, indicating
  that much of a network’s expressivity remains unused but helps gradient descent
  in early stages of training. To characterize the depth of the resulting partially
  linearized network, we introduce a measure called average path length, representing
  the average number of active nonlinearities encountered along a path in the network
  graph. Under sparsity pressure, we find that the remaining nonlinear units organize
  into distinct structures, forming core-networks of near constant effective depth
  and width, which in turn depend on task difficulty.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ali-mehmeti-gopel23a
month: 0
tex_title: 'Nonlinear Advantage: Trained Networks Might Not Be As Complex as You Think'
firstpage: 529
lastpage: 546
page: 529-546
order: 529
cycles: false
bibtex_author: Ali Mehmeti-G\"{o}pel, Christian H.X. and Disselhoff, Jan
author:
- given: Christian H.X.
  family: Ali Mehmeti-Göpel
- given: Jan
  family: Disselhoff
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
pdf: https://proceedings.mlr.press/v202/ali-mehmeti-gopel23a/ali-mehmeti-gopel23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
