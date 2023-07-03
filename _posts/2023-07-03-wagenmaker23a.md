---
title: Leveraging Offline Data in Online Reinforcement Learning
openreview: hFcIR2tUUi
abstract: 'Two central paradigms have emerged in the reinforcement learning (RL) community:
  online RL and offline RL. In the online RL setting, the agent has no prior knowledge
  of the environment, and must interact with it in order to find an $\epsilon$-optimal
  policy. In the offline RL setting, the learner instead has access to a fixed dataset
  to learn from, but is unable to otherwise interact with the environment, and must
  obtain the best policy it can from this offline data. Practical scenarios often
  motivate an intermediate setting: if we have some set of offline data and may also
  interact with the environment, how can we best use the offline data to minimize
  the number of online interactions necessary to learn an $\epsilon$-optimal policy.
  In this work, we consider this setting, which we call the FineTuneRL setting, for
  MDPs with linear structure. We characterize the necessary number of online samples
  needed in this setting given access to some offline dataset, and develop an algorithm,
  FTPedel, which is provably optimal, up to $H$ factors. We show through an explicit
  example that combining offline data with online interactions can lead to a provable
  improvement over either purely offline or purely online RL. Finally, our results
  illustrate the distinction between verifiable learning, the typical setting considered
  in online RL, and unverifiable learning, the setting often considered in offline
  RL, and show that there is a formal separation between these regimes.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: wagenmaker23a
month: 0
tex_title: Leveraging Offline Data in Online Reinforcement Learning
firstpage: 35300
lastpage: 35338
page: 35300-35338
order: 35300
cycles: false
bibtex_author: Wagenmaker, Andrew and Pacchiano, Aldo
author:
- given: Andrew
  family: Wagenmaker
- given: Aldo
  family: Pacchiano
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
pdf: https://proceedings.mlr.press/v202/wagenmaker23a/wagenmaker23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
