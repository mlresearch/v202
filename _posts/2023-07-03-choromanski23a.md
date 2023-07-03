---
title: Taming graph kernels with random features
openreview: H21qm4xyk9
abstract: 'We introduce in this paper the mechanism of graph random features (GRFs).
  GRFs can be used to construct unbiased randomized estimators of several important
  kernels defined on graphs’ nodes, in particular the regularized Laplacian kernel.
  As regular RFs for non-graph kernels, they provide means to scale up kernel methods
  defined on graphs to larger networks. Importantly, they give substantial computational
  gains also for smaller graphs, while applied in downstream applications. Consequently,
  GRFs address the notoriously difficult problem of cubic (in the number of the nodes
  of the graph) time complexity of graph kernels algorithms. We provide a detailed
  theoretical analysis of GRFs and an extensive empirical evaluation: from speed tests,
  through Frobenius relative error analysis to kmeans graph-clustering with graph
  kernels. We show that the computation of GRFs admits an embarrassingly simple distributed
  algorithm that can be applied if the graph under consideration needs to be split
  across several machines. We also introduce a (still unbiased) quasi Monte Carlo
  variant of GRFs, q-GRFs, relying on the so-called reinforced random walks that might
  be used to optimize the variance of GRFs. As a byproduct, we obtain a novel approach
  to solve certain classes of linear equations with positive and symmetric matrices.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: choromanski23a
month: 0
tex_title: Taming graph kernels with random features
firstpage: 5964
lastpage: 5977
page: 5964-5977
order: 5964
cycles: false
bibtex_author: Choromanski, Krzysztof Marcin
author:
- given: Krzysztof Marcin
  family: Choromanski
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
pdf: https://proceedings.mlr.press/v202/choromanski23a/choromanski23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
