---
title: Conformal Prediction Sets for Graph Neural Networks
openreview: zGf8J0bNfX
abstract: Despite the widespread use of graph neural networks (GNNs) we lack methods
  to reliably quantify their uncertainty. We propose a conformal procedure to equip
  GNNs with prediction sets that come with distribution-free guarantees – the output
  set contains the true label with arbitrarily high probability. Our post-processing
  procedure can wrap around any (pretrained) GNN, and unlike existing methods, results
  in meaningful sets even when the model provides only the top class. The key idea
  is to diffuse the node-wise conformity scores to incorporate neighborhood information.
  By leveraging the network homophily we construct sets with comparable or better
  efficiency (average size) and significantly improved singleton hit ratio (correct
  sets of size one). In addition to an extensive empirical evaluation, we investigate
  the theoretical conditions under which smoothing provably improves efficiency.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: h-zargarbashi23a
month: 0
tex_title: Conformal Prediction Sets for Graph Neural Networks
firstpage: 12292
lastpage: 12318
page: 12292-12318
order: 12292
cycles: false
bibtex_author: H. Zargarbashi, Soroush and Antonelli, Simone and Bojchevski, Aleksandar
author:
- given: Soroush
  family: H. Zargarbashi
- given: Simone
  family: Antonelli
- given: Aleksandar
  family: Bojchevski
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
pdf: https://proceedings.mlr.press/v202/h-zargarbashi23a/h-zargarbashi23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
