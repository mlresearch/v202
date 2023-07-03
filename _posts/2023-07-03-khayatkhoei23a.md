---
title: Emergent Asymmetry of Precision and Recall for Measuring Fidelity and Diversity
  of Generative Models in High Dimensions
openreview: D8MLOOGPCg
abstract: Precision and Recall are two prominent metrics of generative performance,
  which were proposed to separately measure the fidelity and diversity of generative
  models. Given their central role in comparing and improving generative models, understanding
  their limitations are crucially important. To that end, in this work, we identify
  a critical flaw in the common approximation of these metrics using k-nearest-neighbors,
  namely, that the very interpretations of fidelity and diversity that are assigned
  to Precision and Recall can fail in high dimensions, resulting in very misleading
  conclusions. Specifically, we empirically and theoretically show that as the number
  of dimensions grows, two model distributions with supports at equal point-wise distance
  from the support of the real distribution, can have vastly different Precision and
  Recall regardless of their respective distributions, hence an emergent asymmetry
  in high dimensions. Based on our theoretical insights, we then provide simple yet
  effective modifications to these metrics to construct symmetric metrics regardless
  of the number of dimensions. Finally, we provide experiments on real-world datasets
  to illustrate that the identified flaw is not merely a pathological case, and that
  our proposed metrics are effective in alleviating its impact.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: khayatkhoei23a
month: 0
tex_title: Emergent Asymmetry of Precision and Recall for Measuring Fidelity and Diversity
  of Generative Models in High Dimensions
firstpage: 16326
lastpage: 16343
page: 16326-16343
order: 16326
cycles: false
bibtex_author: Khayatkhoei, Mahyar and Abdalmageed, Wael
author:
- given: Mahyar
  family: Khayatkhoei
- given: Wael
  family: Abdalmageed
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
pdf: https://proceedings.mlr.press/v202/khayatkhoei23a/khayatkhoei23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
