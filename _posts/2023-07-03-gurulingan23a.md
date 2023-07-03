---
title: Multi-Task Structural Learning using Local Task Similarity induced Neuron Creation
  and Removal
openreview: LZhwwe7j9l
abstract: Multi-task learning has the potential to improve generalization by maximizing
  positive transfer between tasks while reducing task interference. Fully achieving
  this potential is hindered by manually designed architectures that remain static
  throughout training. On the contrary, learning in the brain occurs through structural
  changes that are in tandem with changes in synaptic strength. Thus, we propose <em>Multi-Task
  Structural Learning (MTSL)</em> that simultaneously learns the multi-task architecture
  and its parameters. MTSL begins with an identical single-task network for each task
  and alternates between a task-learning phase and a structural-learning phase. In
  the task learning phase, each network specializes in the corresponding task. In
  each of the structural learning phases, starting from the earliest layer, locally
  similar task layers first transfer their knowledge to a newly created group layer
  before being removed. MTSL then uses the group layer in place of the corresponding
  removed task layers and moves on to the next layers. Our empirical results show
  that MTSL achieves competitive generalization with various baselines and improves
  robustness to out-of-distribution data.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gurulingan23a
month: 0
tex_title: Multi-Task Structural Learning using Local Task Similarity induced Neuron
  Creation and Removal
firstpage: 12205
lastpage: 12223
page: 12205-12223
order: 12205
cycles: false
bibtex_author: Gurulingan, Naresh Kumar and Zonooz, Bahram and Arani, Elahe
author:
- given: Naresh Kumar
  family: Gurulingan
- given: Bahram
  family: Zonooz
- given: Elahe
  family: Arani
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
pdf: https://proceedings.mlr.press/v202/gurulingan23a/gurulingan23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
