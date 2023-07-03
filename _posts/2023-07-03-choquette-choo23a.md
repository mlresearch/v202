---
title: Multi-Epoch Matrix Factorization Mechanisms for Private Machine Learning
openreview: ZVxT2ToHR5
abstract: We introduce new differentially private (DP) mechanisms for gradient-based
  machine learning (ML) with multiple passes (epochs) over a dataset, substantially
  improving the achievable privacy-utility-computation tradeoffs. We formalize the
  problem of DP mechanisms for adaptive streams with multiple participations and introduce
  a non-trivial extension of online matrix factorization DP mechanisms to our setting.
  This includes establishing the necessary theory for sensitivity calculations and
  efficient computation of optimal matrices. For some applications like $>\!\! 10,000$
  SGD steps, applying these optimal techniques becomes computationally expensive.
  We thus design an efficient Fourier-transform-based mechanism with only a minor
  utility loss. Extensive empirical evaluation on both example-level DP for image
  classification and user-level DP for language modeling demonstrate substantial improvements
  over all previous methods, including the widely-used DP-SGD. Though our primary
  application is to ML, our main DP results are applicable to arbitrary linear queries
  and hence may have much broader applicability.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: choquette-choo23a
month: 0
tex_title: Multi-Epoch Matrix Factorization Mechanisms for Private Machine Learning
firstpage: 5924
lastpage: 5963
page: 5924-5963
order: 5924
cycles: false
bibtex_author: Choquette-Choo, Christopher A. and Mcmahan, Hugh Brendan and Rush,
  J Keith and Guha Thakurta, Abhradeep
author:
- given: Christopher A.
  family: Choquette-Choo
- given: Hugh Brendan
  family: Mcmahan
- given: J Keith
  family: Rush
- given: Abhradeep
  family: Guha Thakurta
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
pdf: https://proceedings.mlr.press/v202/choquette-choo23a/choquette-choo23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
