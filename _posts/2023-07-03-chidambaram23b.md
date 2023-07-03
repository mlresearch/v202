---
title: 'Hiding Data Helps: On the Benefits of Masking for Sparse Coding'
openreview: TZvDKSg6im
abstract: Sparse coding, which refers to modeling a signal as sparse linear combinations
  of the elements of a learned dictionary, has proven to be a successful (and interpretable)
  approach in applications such as signal processing, computer vision, and medical
  imaging. While this success has spurred much work on provable guarantees for dictionary
  recovery when the learned dictionary is the same size as the ground-truth dictionary,
  work on the setting where the learned dictionary is larger (or $\textit{over-realized}$)
  with respect to the ground truth is comparatively nascent. Existing theoretical
  results in this setting have been constrained to the case of noise-less data. We
  show in this work that, in the presence of noise, minimizing the standard dictionary
  learning objective can fail to recover the elements of the ground-truth dictionary
  in the over-realized regime, regardless of the magnitude of the signal in the data-generating
  process. Furthermore, drawing from the growing body of work on self-supervised learning,
  we propose a novel masking objective for which recovering the ground-truth dictionary
  is in fact optimal as the signal increases for a large class of data-generating
  processes. We corroborate our theoretical results with experiments across several
  parameter regimes showing that our proposed objective also enjoys better empirical
  performance than the standard reconstruction objective.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chidambaram23b
month: 0
tex_title: 'Hiding Data Helps: On the Benefits of Masking for Sparse Coding'
firstpage: 5600
lastpage: 5615
page: 5600-5615
order: 5600
cycles: false
bibtex_author: Chidambaram, Muthu and Wu, Chenwei and Cheng, Yu and Ge, Rong
author:
- given: Muthu
  family: Chidambaram
- given: Chenwei
  family: Wu
- given: Yu
  family: Cheng
- given: Rong
  family: Ge
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
pdf: https://proceedings.mlr.press/v202/chidambaram23b/chidambaram23b.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
