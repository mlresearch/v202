---
title: The Role of Entropy and Reconstruction in Multi-View Self-Supervised Learning
openreview: YJ3ytyemn1
abstract: The mechanisms behind the success of multi-view self-supervised learning
  (MVSSL) are not yet fully understood. Contrastive MVSSL methods have been studied
  through the lens of InfoNCE, a lower bound of the Mutual Information (MI). However,
  the relation between other MVSSL methods and MI remains unclear. We consider a different
  lower bound on the MI consisting of an entropy and a reconstruction term (ER), and
  analyze the main MVSSL families through its lens. Through this ER bound, we show
  that clustering-based methods such as DeepCluster and SwAV maximize the MI. We also
  re-interpret the mechanisms of distillation-based approaches such as BYOL and DINO,
  showing that they explicitly maximize the reconstruction term and implicitly encourage
  a stable entropy, and we confirm this empirically. We show that replacing the objectives
  of common MVSSL methods with this ER bound achieves competitive performance, while
  making them stable when training with smaller batch sizes or smaller exponential
  moving average (EMA) coefficients.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: rodri-guez-galvez23a
month: 0
tex_title: The Role of Entropy and Reconstruction in Multi-View Self-Supervised Learning
firstpage: 29143
lastpage: 29160
page: 29143-29160
order: 29143
cycles: false
bibtex_author: Rodr\'{\i}guez G\'{a}lvez, Borja and Blaas, Arno and Rodriguez, Pau
  and Golinski, Adam and Suau, Xavier and Ramapuram, Jason and Busbridge, Dan and
  Zappella, Luca
author:
- given: Borja
  family: Rodrı́guez Gálvez
- given: Arno
  family: Blaas
- given: Pau
  family: Rodriguez
- given: Adam
  family: Golinski
- given: Xavier
  family: Suau
- given: Jason
  family: Ramapuram
- given: Dan
  family: Busbridge
- given: Luca
  family: Zappella
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
pdf: https://proceedings.mlr.press/v202/rodri-guez-galvez23a/rodri-guez-galvez23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
