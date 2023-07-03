---
title: 'Synthetic Data, Real Errors: How (Not) to Publish and Use Synthetic Data'
openreview: I5kywOUcl7
abstract: Generating synthetic data through generative models is gaining interest
  in the ML community and beyond, promising a future where datasets can be tailored
  to individual needs. Unfortunately, synthetic data is usually not perfect, resulting
  in potential errors in downstream tasks. In this work we explore how the generative
  process affects the downstream ML task. We show that the naive synthetic data approach—using
  synthetic data as if it is real—leads to downstream models and analyses that do
  not generalize well to real data. As a first step towards better ML in the synthetic
  data regime, we introduce Deep Generative Ensemble (DGE)—a framework inspired by
  Deep Ensembles that aims to implicitly approximate the posterior distribution over
  the generative process model parameters. DGE improves downstream model training,
  evaluation, and uncertainty quantification, vastly outperforming the naive approach
  on average. The largest improvements are achieved for minority classes and low-density
  regions of the original data, for which the generative uncertainty is largest.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: van-breugel23a
month: 0
tex_title: 'Synthetic Data, Real Errors: How ({N}ot) to Publish and Use Synthetic
  Data'
firstpage: 34793
lastpage: 34808
page: 34793-34808
order: 34793
cycles: false
bibtex_author: Van Breugel, Boris and Qian, Zhaozhi and Van Der Schaar, Mihaela
author:
- given: Boris
  family: Van Breugel
- given: Zhaozhi
  family: Qian
- given: Mihaela
  family: Van Der Schaar
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
pdf: https://proceedings.mlr.press/v202/van-breugel23a/van-breugel23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
