---
title: Neural Algorithmic Reasoning with Causal Regularisation
openreview: kP2p67F4G7
abstract: 'Recent work on neural algorithmic reasoning has investigated the reasoning
  capabilities of neural networks, effectively demonstrating they can learn to execute
  classical algorithms on unseen data coming from the train distribution. However,
  the performance of existing neural reasoners significantly degrades on out-of-distribution
  (OOD) test data, where inputs have larger sizes. In this work, we make an important
  observation: there are many different inputs for which an algorithm will perform
  certain intermediate computations identically. This insight allows us to develop
  data augmentation procedures that, given an algorithm’s intermediate trajectory,
  produce inputs for which the target algorithm would have exactly the same next trajectory
  step. We ensure invariance in the next-step prediction across such inputs, by employing
  a self-supervised objective derived by our observation, formalised in a causal graph.
  We prove that the resulting method, which we call Hint-ReLIC, improves the OOD generalisation
  capabilities of the reasoner. We evaluate our method on the CLRS algorithmic reasoning
  benchmark, where we show up to 3x improvements on the OOD test data.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bevilacqua23a
month: 0
tex_title: Neural Algorithmic Reasoning with Causal Regularisation
firstpage: 2272
lastpage: 2288
page: 2272-2288
order: 2272
cycles: false
bibtex_author: Bevilacqua, Beatrice and Nikiforou, Kyriacos and Ibarz, Borja and Bica,
  Ioana and Paganini, Michela and Blundell, Charles and Mitrovic, Jovana and Veli\v{c}kovi\'{c},
  Petar
author:
- given: Beatrice
  family: Bevilacqua
- given: Kyriacos
  family: Nikiforou
- given: Borja
  family: Ibarz
- given: Ioana
  family: Bica
- given: Michela
  family: Paganini
- given: Charles
  family: Blundell
- given: Jovana
  family: Mitrovic
- given: Petar
  family: Veličković
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
pdf: https://proceedings.mlr.press/v202/bevilacqua23a/bevilacqua23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
