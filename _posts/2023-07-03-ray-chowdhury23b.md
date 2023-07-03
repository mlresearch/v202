---
title: Monotonic Location Attention for Length Generalization
openreview: 6clNOzWjgY
abstract: We explore different ways to utilize position-based cross-attention in seq2seq
  networks to enable length generalization in algorithmic tasks. We show that a simple
  approach of interpolating the original and reversed encoded representations combined
  with relative attention allows near-perfect length generalization for both forward
  and reverse lookup tasks or copy tasks that had been generally hard to tackle. We
  also devise harder diagnostic tasks where the relative distance of the ideal attention
  position varies with timestep. In such settings, the simple interpolation trick
  with relative attention is not sufficient. We introduce novel variants of location
  attention building on top of Dubois et al. (2020) to address the new diagnostic
  tasks. We also show the benefits of our approaches for length generalization in
  SCAN (Lake & Baroni, 2018) and CFQ (Keysers et al.,2020). Our code is available
  on GitHub.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ray-chowdhury23b
month: 0
tex_title: Monotonic Location Attention for Length Generalization
firstpage: 28792
lastpage: 28808
page: 28792-28808
order: 28792
cycles: false
bibtex_author: Ray Chowdhury, Jishnu and Caragea, Cornelia
author:
- given: Jishnu
  family: Ray Chowdhury
- given: Cornelia
  family: Caragea
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
pdf: https://proceedings.mlr.press/v202/ray-chowdhury23b/ray-chowdhury23b.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
