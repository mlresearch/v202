---
title: Adaptive IMLE for Few-shot Pretraining-free Generative Modelling
openreview: CNq0JvrDfw
abstract: Despite their success on large datasets, GANs have been difficult to apply
  in the few-shot setting, where only a limited number of training examples are provided.
  Due to mode collapse, GANs tend to ignore some training examples, causing overfitting
  to a subset of the training dataset, which is small in the first place. A recent
  method called Implicit Maximum Likelihood Estimation (IMLE) is an alternative to
  GAN that tries to address this issue. It uses the same kind of generators as GANs
  but trains it with a different objective that encourages mode coverage. However,
  the theoretical guarantees of IMLE hold under a restrictive condition that the optimal
  likelihood at all data points is the same. In this paper, we present a more generalized
  formulation of IMLE which includes the original formulation as a special case, and
  we prove that the theoretical guarantees hold under weaker conditions. Using this
  generalized formulation, we further derive a new algorithm, which we dub Adaptive
  IMLE, which can adapt to the varying difficulty of different training examples.
  We demonstrate on multiple few-shot image synthesis datasets that our method significantly
  outperforms existing methods. Our code is available at https://github.com/mehranagh20/AdaIMLE.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: aghabozorgi23a
month: 0
tex_title: Adaptive {IMLE} for Few-shot Pretraining-free Generative Modelling
firstpage: 248
lastpage: 264
page: 248-264
order: 248
cycles: false
bibtex_author: Aghabozorgi, Mehran and Peng, Shichong and Li, Ke
author:
- given: Mehran
  family: Aghabozorgi
- given: Shichong
  family: Peng
- given: Ke
  family: Li
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
pdf: https://proceedings.mlr.press/v202/aghabozorgi23a/aghabozorgi23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
