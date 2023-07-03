---
title: Diffusion Models for Black-Box Optimization
openreview: hQCgc6T15R
abstract: The goal of offline black-box optimization (BBO) is to optimize an expensive
  black-box function using a fixed dataset of function evaluations. Prior works consider
  forward approaches that learn surrogates to the black-box function and inverse approaches
  that directly map function values to corresponding points in the input domain of
  the black-box function. These approaches are limited by the quality of the offline
  dataset and the difficulty in learning one-to-many mappings in high dimensions,
  respectively. We propose Denoising Diffusion Optimization Models (DDOM), a new inverse
  approach for offline black-box optimization based on diffusion models. Given an
  offline dataset, DDOM learns a conditional generative model over the domain of the
  black-box function conditioned on the function values. We investigate several design
  choices in DDOM, such as reweighting the dataset to focus on high function values
  and the use of classifier-free guidance at test-time to enable generalization to
  function values that can even exceed the dataset maxima. Empirically, we conduct
  experiments on the Design-Bench benchmark (Trabucco et al., 2022) and show that
  DDOM achieves results competitive with state-of-the-art baselines.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: krishnamoorthy23a
month: 0
tex_title: Diffusion Models for Black-Box Optimization
firstpage: 17842
lastpage: 17857
page: 17842-17857
order: 17842
cycles: false
bibtex_author: Krishnamoorthy, Siddarth and Mashkaria, Satvik Mehul and Grover, Aditya
author:
- given: Siddarth
  family: Krishnamoorthy
- given: Satvik Mehul
  family: Mashkaria
- given: Aditya
  family: Grover
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
pdf: https://proceedings.mlr.press/v202/krishnamoorthy23a/krishnamoorthy23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
