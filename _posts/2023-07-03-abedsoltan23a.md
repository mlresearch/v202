---
title: Toward Large Kernel Models
openreview: fCyg20LQsL
abstract: Recent studies indicate that kernel machines can often perform similarly
  or better than deep neural networks (DNNs) on small datasets. The interest in kernel
  machines has been additionally bolstered by the discovery of their equivalence to
  wide neural networks in certain regimes. However, a key feature of DNNs is their
  ability to scale the model size and training data size independently, whereas in
  traditional kernel machines model size is tied to data size. Because of this coupling,
  scaling kernel machines to large data has been computationally challenging. In this
  paper, we provide a way forward for constructing large-scale general kernel models,
  which are a generalization of kernel machines that decouples the model and data,
  allowing training on large datasets. Specifically, we introduce EigenPro 3.0, an
  algorithm based on projected dual preconditioned SGD and show scaling to model and
  data sizes which have not been possible with existing kernel methods. We provide
  a PyTorch based implementation which can take advantage of multiple GPUs.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: abedsoltan23a
month: 0
tex_title: Toward Large Kernel Models
firstpage: 61
lastpage: 78
page: 61-78
order: 61
cycles: false
bibtex_author: Abedsoltan, Amirhesam and Belkin, Mikhail and Pandit, Parthe
author:
- given: Amirhesam
  family: Abedsoltan
- given: Mikhail
  family: Belkin
- given: Parthe
  family: Pandit
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
pdf: https://proceedings.mlr.press/v202/abedsoltan23a/abedsoltan23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
