---
title: Improving Expert Predictions with Conformal Prediction
openreview: tgm43aFDXD
abstract: Automated decision support systems promise to help human experts solve multiclass
  classification tasks more efficiently and accurately. However, existing systems
  typically require experts to understand when to cede agency to the system or when
  to exercise their own agency. Otherwise, the experts may be better off solving the
  classification tasks on their own. In this work, we develop an automated decision
  support system that, by design, does not require experts to understand when to trust
  the system to improve performance. Rather than providing (single) label predictions
  and letting experts decide when to trust these predictions, our system provides
  sets of label predictions constructed using conformal prediction—prediction sets—and
  forcefully asks experts to predict labels from these sets. By using conformal prediction,
  our system can precisely trade-off the probability that the true label is not in
  the prediction set, which determines how frequently our system will mislead the
  experts, and the size of the prediction set, which determines the difficulty of
  the classification task the experts need to solve using our system. In addition,
  we develop an efficient and near-optimal search method to find the conformal predictor
  under which the experts benefit the most from using our system. Simulation experiments
  using synthetic and real expert predictions demonstrate that our system may help
  experts make more accurate predictions and is robust to the accuracy of the classifier
  the conformal predictor relies on.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: straitouri23a
month: 0
tex_title: Improving Expert Predictions with Conformal Prediction
firstpage: 32633
lastpage: 32653
page: 32633-32653
order: 32633
cycles: false
bibtex_author: Straitouri, Eleni and Wang, Lequn and Okati, Nastaran and Gomez Rodriguez,
  Manuel
author:
- given: Eleni
  family: Straitouri
- given: Lequn
  family: Wang
- given: Nastaran
  family: Okati
- given: Manuel
  family: Gomez Rodriguez
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
pdf: https://proceedings.mlr.press/v202/straitouri23a/straitouri23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
