---
title: Statistical Learning under Heterogenous Distribution Shift
openreview: MEnEJqyE4s
abstract: This paper studies the prediction of a target $\mathbf{z}$ from a pair of
  random variables $(\mathbf{x},\mathbf{y})$, where the ground-truth predictor is
  additive $\mathbb{E}[\mathbf{z} \mid \mathbf{x},\mathbf{y}] = f_\star(\mathbf{x})
  +g_{\star}(\mathbf{y})$. We study the performance of empirical risk minimization
  (ERM) over functions $f+g$, $f \in \mathcal{F}$ and $g \in \mathcal{G}$, fit on
  a given training distribution, but evaluated on a test distribution which exhibits
  covariate shift. We show that, when the class $\mathcal{F}$ is "simpler" than $\mathcal{G}$
  (measured, e.g., in terms of its metric entropy), our predictor is more resilient
  to <em>heterogenous covariate shifts</em> in which the shift in $\mathbf{x}$ is
  much greater than that in $\mathbf{y}$. These results rely on a novel Hölder style
  inequality for the Dudley integral which may be of independent interest. Moreover,
  we corroborate our theoretical findings with experiments demonstrating improved
  resilience to shifts in "simpler" features across numerous domains.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: simchowitz23a
month: 0
tex_title: Statistical Learning under Heterogenous Distribution Shift
firstpage: 31800
lastpage: 31851
page: 31800-31851
order: 31800
cycles: false
bibtex_author: Simchowitz, Max and Ajay, Anurag and Agrawal, Pulkit and Krishnamurthy,
  Akshay
author:
- given: Max
  family: Simchowitz
- given: Anurag
  family: Ajay
- given: Pulkit
  family: Agrawal
- given: Akshay
  family: Krishnamurthy
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
pdf: https://proceedings.mlr.press/v202/simchowitz23a/simchowitz23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
