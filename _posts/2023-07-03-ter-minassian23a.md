---
title: 'PWSHAP: A Path-Wise Explanation Model for Targeted Variables'
openreview: u8VEJNykA5
abstract: Predictive black-box models can exhibit high-accuracy but their opaque nature
  hinders their uptake in safety-critical deployment environments. Explanation methods
  (XAI) can provide confidence for decision-making through increased transparency.
  However, existing XAI methods are not tailored towards models in sensitive domains
  where one predictor is of special interest, such as a treatment effect in a clinical
  model, or ethnicity in policy models. We introduce Path-Wise Shapley effects (PWSHAP),
  a framework for assessing the targeted effect of a binary (e.g. treatment) variable
  from a complex outcome model. Our approach augments the predictive model with a
  user-defined directed acyclic graph (DAG). The method then uses the graph alongside
  on-manifold Shapley values to identify effects along causal pathways whilst maintaining
  robustness to adversarial attacks. We establish error bounds for the identified
  path-wise Shapley effects and for Shapley values. We show PWSHAP can perform local
  bias and mediation analyses with faithfulness to the model. Further, if the targeted
  variable is randomised we can quantify local effect modification. We demonstrate
  the resolution, interpretability and true locality of our approach on examples and
  a real-world experiment.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ter-minassian23a
month: 0
tex_title: "{PWSHAP}: A Path-Wise Explanation Model for Targeted Variables"
firstpage: 34054
lastpage: 34089
page: 34054-34089
order: 34054
cycles: false
bibtex_author: Ter-Minassian, Lucile and Clivio, Oscar and Diazordaz, Karla and Evans,
  Robin J. and Holmes, Christopher C.
author:
- given: Lucile
  family: Ter-Minassian
- given: Oscar
  family: Clivio
- given: Karla
  family: Diazordaz
- given: Robin J.
  family: Evans
- given: Christopher C.
  family: Holmes
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
pdf: https://proceedings.mlr.press/v202/ter-minassian23a/ter-minassian23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
