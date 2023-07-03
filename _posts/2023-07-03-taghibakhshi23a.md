---
title: 'MG-GNN: Multigrid Graph Neural Networks for Learning Multilevel Domain Decomposition
  Methods'
openreview: bkRrdYhd7U
abstract: Domain decomposition methods (DDMs) are popular solvers for discretized
  systems of partial differential equations (PDEs), with one-level and multilevel
  variants. These solvers rely on several algorithmic and mathematical parameters,
  prescribing overlap, subdomain boundary conditions, and other properties of the
  DDM. While some work has been done on optimizing these parameters, it has mostly
  focused on the one-level setting or special cases such as structured-grid discretizations
  with regular subdomain construction. In this paper, we propose multigrid graph neural
  networks (MG-GNN), a novel GNN architecture for learning optimized parameters in
  two-level DDMs. We train MG-GNN using a new unsupervised loss function, enabling
  effective training on small problems that yields robust performance on unstructured
  grids that are orders of magnitude larger than those in the training set. We show
  that MG-GNN outperforms popular hierarchical graph network architectures for this
  optimization and that our proposed loss function is critical to achieving this improved
  performance.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: taghibakhshi23a
month: 0
tex_title: "{MG}-{GNN}: Multigrid Graph Neural Networks for Learning Multilevel Domain
  Decomposition Methods"
firstpage: 33381
lastpage: 33395
page: 33381-33395
order: 33381
cycles: false
bibtex_author: Taghibakhshi, Ali and Nytko, Nicolas and Zaman, Tareq Uz and Maclachlan,
  Scott and Olson, Luke and West, Matthew
author:
- given: Ali
  family: Taghibakhshi
- given: Nicolas
  family: Nytko
- given: Tareq Uz
  family: Zaman
- given: Scott
  family: Maclachlan
- given: Luke
  family: Olson
- given: Matthew
  family: West
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
pdf: https://proceedings.mlr.press/v202/taghibakhshi23a/taghibakhshi23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
