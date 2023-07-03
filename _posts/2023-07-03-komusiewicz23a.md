---
title: On Computing Optimal Tree Ensembles
openreview: w5xlapg9L5
abstract: Random forests and, more generally, (decision-)tree ensembles are widely
  used methods for classification and regression. Recent algorithmic advances allow
  to compute decision trees that are optimal for various measures such as their size
  or depth. We are not aware of such research for tree ensembles and aim to contribute
  to this area. Mainly, we provide two novel algorithms and corresponding lower bounds.
  First, we are able to carry over and substantially improve on tractability results
  for decision trees, obtaining a $(6\delta D S)^S \cdot \mathrm{poly}$-time algorithm,
  where $S$ is the number of cuts in the tree ensemble, $D$ the largest domain size,
  and $\delta$ is the largest number of features in which two examples differ. To
  achieve this, we introduce the witness-tree technique which also seems promising
  for practice. Second, we show that dynamic programming, which has been successful
  for decision trees, may also be viable for tree ensembles, providing an $\ell^n
  \cdot \mathrm{poly}$-time algorithm, where $\ell$ is the number of trees and $n$
  the number of examples. Finally, we compare the number of cuts necessary to classify
  training data sets for decision trees and tree ensembles, showing that ensembles
  may need exponentially fewer cuts for increasing number of trees.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: komusiewicz23a
month: 0
tex_title: On Computing Optimal Tree Ensembles
firstpage: 17364
lastpage: 17374
page: 17364-17374
order: 17364
cycles: false
bibtex_author: Komusiewicz, Christian and Kunz, Pascal and Sommer, Frank and Sorge,
  Manuel
author:
- given: Christian
  family: Komusiewicz
- given: Pascal
  family: Kunz
- given: Frank
  family: Sommer
- given: Manuel
  family: Sorge
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
pdf: https://proceedings.mlr.press/v202/komusiewicz23a/komusiewicz23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
