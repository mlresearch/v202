---
title: Test-time Adaptation with Slot-Centric Models
openreview: G5vKSJVhJL
abstract: 'Current visual detectors, though impressive within their training distribution,
  often fail to parse out-of-distribution scenes into their constituent entities.
  Recent test-time adaptation methods use auxiliary self-supervised losses to adapt
  the network parameters to each test example independently and have shown promising
  results towards generalization outside the training distribution for the task of
  image classification. In our work, we find evidence that these losses are insufficient
  for the task of scene decomposition, without also considering architectural inductive
  biases. Recent slot-centric generative models attempt to decompose scenes into entities
  in a self-supervised manner by reconstructing pixels. Drawing upon these two lines
  of work, we propose Slot-TTA, a semi-supervised slot-centric scene decomposition
  model that at test time is adapted per scene through gradient descent on reconstruction
  or cross-view synthesis objectives. We evaluate Slot-TTA across multiple input modalities,
  images or 3D point clouds, and show substantial out-of-distribution performance
  improvements against state-of-the-art supervised feed-forward detectors, and alternative
  test-time adaptation methods. Project Webpage: http://slot-tta.github.io/'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: prabhudesai23a
month: 0
tex_title: Test-time Adaptation with Slot-Centric Models
firstpage: 28151
lastpage: 28166
page: 28151-28166
order: 28151
cycles: false
bibtex_author: Prabhudesai, Mihir and Goyal, Anirudh and Paul, Sujoy and Steenkiste,
  Sjoerd Van and Sajjadi, Mehdi S. M. and Aggarwal, Gaurav and Kipf, Thomas and Pathak,
  Deepak and Fragkiadaki, Katerina
author:
- given: Mihir
  family: Prabhudesai
- given: Anirudh
  family: Goyal
- given: Sujoy
  family: Paul
- given: Sjoerd Van
  family: Steenkiste
- given: Mehdi S. M.
  family: Sajjadi
- given: Gaurav
  family: Aggarwal
- given: Thomas
  family: Kipf
- given: Deepak
  family: Pathak
- given: Katerina
  family: Fragkiadaki
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
pdf: https://proceedings.mlr.press/v202/prabhudesai23a/prabhudesai23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
