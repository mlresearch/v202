---
title: Fully-Adaptive Composition in Differential Privacy
openreview: pMQciTD4vb
abstract: 'Composition is a key feature of differential privacy. Well-known advanced
  composition theorems allow one to query a private database quadratically more times
  than basic privacy composition would permit. However, these results require that
  the privacy parameters of all algorithms be fixed before interacting with the data.
  To address this, Rogers et al. introduced fully adaptive composition, wherein both
  algorithms and their privacy parameters can be selected adaptively. They defined
  two probabilistic objects to measure privacy in adaptive composition: privacy filters,
  which provide differential privacy guarantees for composed interactions, and privacy
  odometers, time-uniform bounds on privacy loss. There are substantial gaps between
  advanced composition and existing filters and odometers. First, existing filters
  place stronger assumptions on the algorithms being composed. Second, these odometers
  and filters suffer from large constants, making them impractical. We construct filters
  that match the rates of advanced composition, including constants, despite allowing
  for adaptively chosen privacy parameters. En route we also derive a privacy filter
  for approximate zCDP. We also construct several general families of odometers. These
  odometers match the tightness of advanced composition at an arbitrary, preselected
  point in time, or at all points in time simultaneously, up to a doubly-logarithmic
  factor. We obtain our results by leveraging advances in martingale concentration.
  In sum, we show that fully adaptive privacy is obtainable at almost no loss.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: whitehouse23a
month: 0
tex_title: Fully-Adaptive Composition in Differential Privacy
firstpage: 36990
lastpage: 37007
page: 36990-37007
order: 36990
cycles: false
bibtex_author: Whitehouse, Justin and Ramdas, Aaditya and Rogers, Ryan and Wu, Steven
author:
- given: Justin
  family: Whitehouse
- given: Aaditya
  family: Ramdas
- given: Ryan
  family: Rogers
- given: Steven
  family: Wu
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
pdf: https://proceedings.mlr.press/v202/whitehouse23a/whitehouse23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
