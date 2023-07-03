---
title: Causal Bounds in Quasi-Markovian Graphs
openreview: eXtJRDCGye
abstract: We consider the problem of computing bounds for causal queries on quasi-Markovian
  graphs with unobserved confounders and discrete valued observed variables, where
  identifiability does not hold. Existing non-parametric approaches for computing
  such bounds use multilinear programming (MP) formulations that are often intractable
  for existing solvers when the degree of the polynomial objective is greater than
  two. Hence, one often has to resort to either fast approximate heuristics which
  are not guaranteed to contain the true query value, or more accurate but computationally
  intensive procedures. We show how to construct an equivalent MP with a polynomial
  objective of lower degree. In particular, the degree of the objective in the new
  MP is equal to only the number of C-components that are intervened upon, instead
  of the total number of C-components. As a result, we can compute exact bounds for
  significantly larger causal inference problems as compared to what is possible using
  existing techniques. We also propose a very efficient Frank-Wolfe heuristic that
  produces very high quality bounds, and scales to large multilinear problems of higher
  degree.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: shridharan23a
month: 0
tex_title: Causal Bounds in Quasi-{M}arkovian Graphs
firstpage: 31675
lastpage: 31692
page: 31675-31692
order: 31675
cycles: false
bibtex_author: Shridharan, Madhumitha and Iyengar, Garud
author:
- given: Madhumitha
  family: Shridharan
- given: Garud
  family: Iyengar
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
pdf: https://proceedings.mlr.press/v202/shridharan23a/shridharan23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
