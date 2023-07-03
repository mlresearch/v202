---
title: Hierarchies of Reward Machines
openreview: qrH8ERUBcE
abstract: Reward machines (RMs) are a recent formalism for representing the reward
  function of a reinforcement learning task through a finite-state machine whose edges
  encode subgoals of the task using high-level events. The structure of RMs enables
  the decomposition of a task into simpler and independently solvable subtasks that
  help tackle long-horizon and/or sparse reward tasks. We propose a formalism for
  further abstracting the subtask structure by endowing an RM with the ability to
  call other RMs, thus composing a hierarchy of RMs (HRM). We exploit HRMs by treating
  each call to an RM as an independently solvable subtask using the options framework,
  and describe a curriculum-based method to learn HRMs from traces observed by the
  agent. Our experiments reveal that exploiting a handcrafted HRM leads to faster
  convergence than with a flat HRM, and that learning an HRM is feasible in cases
  where its equivalent flat representation is not.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: furelos-blanco23a
month: 0
tex_title: Hierarchies of Reward Machines
firstpage: 10494
lastpage: 10541
page: 10494-10541
order: 10494
cycles: false
bibtex_author: Furelos-Blanco, Daniel and Law, Mark and Jonsson, Anders and Broda,
  Krysia and Russo, Alessandra
author:
- given: Daniel
  family: Furelos-Blanco
- given: Mark
  family: Law
- given: Anders
  family: Jonsson
- given: Krysia
  family: Broda
- given: Alessandra
  family: Russo
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
pdf: https://proceedings.mlr.press/v202/furelos-blanco23a/furelos-blanco23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
