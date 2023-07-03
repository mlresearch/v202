---
title: How much does Initialization Affect Generalization?
openreview: FLhE8qzOmo
abstract: Characterizing the remarkable generalization properties of over-parameterized
  neural networks remains an open problem. A growing body of recent literature shows
  that the bias of stochastic gradient descent (SGD) and architecture choice implicitly
  leads to better generalization. In this paper, we show on the contrary that, independently
  of architecture, SGD can itself be the cause of poor generalization if one does
  not ensure good initialization. Specifically, we prove that <em>any</em> differentiably
  parameterized model, trained under gradient flow, obeys a weak spectral bias law
  which states that sufficiently high frequencies train arbitrarily slowly. This implies
  that very high frequencies present at initialization will remain after training,
  and hamper generalization. Further, we empirically test the developed theoretical
  insights using practical, deep networks. Finally, we contrast our framework with
  that supplied by the <em>flat-minima</em> conjecture and show that Fourier analysis
  grants a more reliable framework for understanding the generalization of neural
  networks.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ramasinghe23a
month: 0
tex_title: How much does Initialization Affect Generalization?
firstpage: 28637
lastpage: 28655
page: 28637-28655
order: 28637
cycles: false
bibtex_author: Ramasinghe, Sameera and Macdonald, Lachlan Ewen and Farazi, Moshiur
  and Saratchandran, Hemanth and Lucey, Simon
author:
- given: Sameera
  family: Ramasinghe
- given: Lachlan Ewen
  family: Macdonald
- given: Moshiur
  family: Farazi
- given: Hemanth
  family: Saratchandran
- given: Simon
  family: Lucey
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
pdf: https://proceedings.mlr.press/v202/ramasinghe23a/ramasinghe23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
