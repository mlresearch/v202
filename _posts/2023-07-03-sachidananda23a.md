---
title: Global Selection of Contrastive Batches via Optimization on Sample Permutations
openreview: 3gLPC1VtDz
abstract: Contrastive Learning has recently achieved state-of-the-art performance
  in a wide range of unimodal and multimodal tasks. Many contrastive learning approaches
  use mined hard negatives to make batches more informative during training but these
  approaches are inefficient as they increase epoch length proportional to the number
  of mined negatives and require frequent updates of nearest neighbor indices or mining
  from recent batches. In this work, we provide an alternative to hard negative mining,
  Global Contrastive Batch Sampling (GCBS), an efficient approximation to the batch
  assignment problem that upper bounds the gap between the global and training losses,
  $\mathcal{L}^{Global} - \mathcal{L}^{Train}$, in contrastive learning settings.
  Through experimentation we find GCBS improves state-of-the-art performance in sentence
  embedding and code-search tasks. Additionally, GCBS is easy to implement as it requires
  only a few additional lines of code, does not maintain external data structures
  such as nearest neighbor indices, is more computationally efficient than the most
  minimal hard negative mining approaches, and makes no changes to the model being
  trained. Code is available at https://github.com/vinayak1/GCBS.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sachidananda23a
month: 0
tex_title: Global Selection of Contrastive Batches via Optimization on Sample Permutations
firstpage: 29542
lastpage: 29562
page: 29542-29562
order: 29542
cycles: false
bibtex_author: Sachidananda, Vin and Yang, Ziyi and Zhu, Chenguang
author:
- given: Vin
  family: Sachidananda
- given: Ziyi
  family: Yang
- given: Chenguang
  family: Zhu
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
pdf: https://proceedings.mlr.press/v202/sachidananda23a/sachidananda23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
