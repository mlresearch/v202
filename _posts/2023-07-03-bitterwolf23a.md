---
title: In or Out? Fixing ImageNet Out-of-Distribution Detection Evaluation
openreview: ChniRIfpRR
abstract: 'Out-of-distribution (OOD) detection is the problem of identifying inputs
  which are unrelated to the in-distribution task. The OOD detection performance when
  the in-distribution (ID) is ImageNet-1K is commonly being tested on a small range
  of test OOD datasets. We find that most of the currently used test OOD datasets,
  including datasets from the open set recognition (OSR) literature, have severe issues:
  In some cases more than 50$%$ of the dataset contains objects belonging to one of
  the ID classes. These erroneous samples heavily distort the evaluation of OOD detectors.
  As a solution, we introduce with NINCO a novel test OOD dataset, each sample checked
  to be ID free, which with its fine-grained range of OOD classes allows for a detailed
  analysis of an OOD detector’s strengths and failure modes, particularly when paired
  with a number of synthetic “OOD unit-tests”. We provide detailed evaluations across
  a large set of architectures and OOD detection methods on NINCO and the unit-tests,
  revealing new insights about model weaknesses and the effects of pretraining on
  OOD detection performance. We provide code and data at https://github.com/j-cb/NINCO.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bitterwolf23a
month: 0
tex_title: In or Out? {F}ixing {I}mage{N}et Out-of-Distribution Detection Evaluation
firstpage: 2471
lastpage: 2506
page: 2471-2506
order: 2471
cycles: false
bibtex_author: Bitterwolf, Julian and M\"{u}ller, Maximilian and Hein, Matthias
author:
- given: Julian
  family: Bitterwolf
- given: Maximilian
  family: Müller
- given: Matthias
  family: Hein
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
pdf: https://proceedings.mlr.press/v202/bitterwolf23a/bitterwolf23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
