---
title: Label differential privacy and private training data release
openreview: K1sJiHvy02
abstract: We study differentially private mechanisms for sharing training data in
  machine learning settings. Our goal is to enable learning of an accurate predictive
  model while protecting the privacy of each user’s label. Previous work established
  privacy guarantees that assumed the features are public and given exogenously, a
  setting known as label differential privacy. In some scenarios, this can be a strong
  assumption that removes the interplay between features and labels from the privacy
  analysis. We relax this approach and instead assume the features are drawn from
  a distribution that depends on the private labels. We first show that simply adding
  noise to the label, as in previous work, can lead to an arbitrarily weak privacy
  guarantee, and also present methods for estimating this privacy loss from data.
  We then present a new mechanism that replaces some training examples with synthetically
  generated data, and show that our mechanism has a much better privacy-utility tradeoff
  if the synthetic data is ‘realistic’, in a certain quantifiable sense. Finally,
  we empirically validate our theoretical analysis.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: busa-fekete23a
month: 0
tex_title: Label differential privacy and private training data release
firstpage: 3233
lastpage: 3251
page: 3233-3251
order: 3233
cycles: false
bibtex_author: Busa-Fekete, Robert Istvan and Munoz Medina, Andres and Syed, Umar
  and Vassilvitskii, Sergei
author:
- given: Robert Istvan
  family: Busa-Fekete
- given: Andres
  family: Munoz Medina
- given: Umar
  family: Syed
- given: Sergei
  family: Vassilvitskii
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
pdf: https://proceedings.mlr.press/v202/busa-fekete23a/busa-fekete23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
