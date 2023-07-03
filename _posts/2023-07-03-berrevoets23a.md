---
title: Differentiable and Transportable Structure Learning
openreview: 8pCLQsEMPQ
abstract: 'Directed acyclic graphs (DAGs) encode a lot of information about a particular
  distribution in their structure. However, compute required to infer these structures
  is typically super-exponential in the number of variables, as inference requires
  a sweep of a combinatorially large space of potential structures. That is, until
  recent advances made it possible to search this space using a differentiable metric,
  drastically reducing search time. While this technique— named NOTEARS —is widely
  considered a seminal work in DAG-discovery, it concedes an important property in
  favour of differentiability: transportability. To be transportable, the structures
  discovered on one dataset must apply to another dataset from the same domain. We
  introduce D-Struct which recovers transportability in the discovered structures
  through a novel architecture and loss function while remaining fully differentiable.
  Because D-Struct remains differentiable, our method can be easily adopted in existing
  differentiable architectures, as was previously done with NOTEARS. In our experiments,
  we empirically validate D-Struct with respect to edge accuracy and structural Hamming
  distance in a variety of settings.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: berrevoets23a
month: 0
tex_title: Differentiable and Transportable Structure Learning
firstpage: 2206
lastpage: 2233
page: 2206-2233
order: 2206
cycles: false
bibtex_author: Berrevoets, Jeroen and Seedat, Nabeel and Imrie, Fergus and Van Der
  Schaar, Mihaela
author:
- given: Jeroen
  family: Berrevoets
- given: Nabeel
  family: Seedat
- given: Fergus
  family: Imrie
- given: Mihaela
  family: Van Der Schaar
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
pdf: https://proceedings.mlr.press/v202/berrevoets23a/berrevoets23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
