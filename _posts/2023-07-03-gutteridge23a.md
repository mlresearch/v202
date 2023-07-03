---
title: 'DRew: Dynamically Rewired Message Passing with Delay'
openreview: WEgjbJ6IDN
abstract: Message passing neural networks (MPNNs) have been shown to suffer from the
  phenomenon of over-squashing that causes poor performance for tasks relying on long-range
  interactions. This can be largely attributed to message passing only occurring locally,
  over a node’s immediate neighbours. Rewiring approaches attempting to make graphs
  ’more connected’, and supposedly better suited to long-range tasks, often lose the
  inductive bias provided by distance on the graph since they make distant nodes communicate
  instantly at every layer. In this paper we propose a framework, applicable to any
  MPNN architecture, that performs a layer-dependent rewiring to ensure gradual densification
  of the graph. We also propose a delay mechanism that permits skip connections between
  nodes depending on the layer and their mutual distance. We validate our approach
  on several long-range tasks and show that it outperforms graph Transformers and
  multi-hop MPNNs.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gutteridge23a
month: 0
tex_title: "{DR}ew: Dynamically Rewired Message Passing with Delay"
firstpage: 12252
lastpage: 12267
page: 12252-12267
order: 12252
cycles: false
bibtex_author: Gutteridge, Benjamin and Dong, Xiaowen and Bronstein, Michael M. and
  Di Giovanni, Francesco
author:
- given: Benjamin
  family: Gutteridge
- given: Xiaowen
  family: Dong
- given: Michael M.
  family: Bronstein
- given: Francesco
  family: Di Giovanni
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
pdf: https://proceedings.mlr.press/v202/gutteridge23a/gutteridge23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
