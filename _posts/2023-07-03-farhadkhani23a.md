---
title: Robust Collaborative Learning with Linear Gradient Overhead
openreview: BkVWMrgb7K
abstract: Collaborative learning algorithms, such as distributed SGD (or D-SGD), are
  prone to faulty machines that may deviate from their prescribed algorithm because
  of software or hardware bugs, poisoned data or malicious behaviors. While many solutions
  have been proposed to enhance the robustness of D-SGD to such machines, previous
  works either resort to strong assumptions (trusted server, homogeneous data, specific
  noise model) or impose a gradient computational cost that is several orders of magnitude
  higher than that of D-SGD. We present MoNNA, a new algorithm that (a) is provably
  robust under standard assumptions and (b) has a gradient computation overhead that
  is linear in the fraction of faulty machines, which is conjectured to be tight.
  Essentially, MoNNA uses Polyak’s momentum of local gradients for local updates and
  nearest-neighbor averaging (NNA) for global mixing, respectively. While MoNNA is
  rather simple to implement, its analysis has been more challenging and relies on
  two key elements that may be of independent interest. Specifically, we introduce
  the mixing criterion of $(\alpha, \lambda)$-reduction to analyze the non-linear
  mixing of non-faulty machines, and present a way to control the tension between
  the momentum and the model drifts. We validate our theory by experiments on image
  classification and make our code available at https://github.com/LPD-EPFL/robust-collaborative-learning.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: farhadkhani23a
month: 0
tex_title: Robust Collaborative Learning with Linear Gradient Overhead
firstpage: 9761
lastpage: 9813
page: 9761-9813
order: 9761
cycles: false
bibtex_author: Farhadkhani, Sadegh and Guerraoui, Rachid and Gupta, Nirupam and Hoang,
  L\^{e}-Nguy\^{e}n and Pinot, Rafael and Stephan, John
author:
- given: Sadegh
  family: Farhadkhani
- given: Rachid
  family: Guerraoui
- given: Nirupam
  family: Gupta
- given: Lê-Nguyên
  family: Hoang
- given: Rafael
  family: Pinot
- given: John
  family: Stephan
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
pdf: https://proceedings.mlr.press/v202/farhadkhani23a/farhadkhani23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
