---
title: 'Gaussian processes at the Helm(holtz): A more fluid model for ocean currents'
openreview: Qtix8HLmDx
abstract: Oceanographers are interested in predicting ocean currents and identifying
  divergences in a current vector field based on sparse observations of buoy velocities.
  Since we expect current dynamics to be smooth but highly non-linear, Gaussian processes
  (GPs) offer an attractive model. But we show that applying a GP with a standard
  stationary kernel directly to buoy data can struggle at both current prediction
  and divergence identification – due to some physically unrealistic prior assumptions.
  To better reflect known physical properties of currents, we propose to instead put
  a standard stationary kernel on the divergence and curl-free components of a vector
  field obtained through a Helmholtz decomposition. We show that, because this decomposition
  relates to the original vector field just via mixed partial derivatives, we can
  still perform inference given the original data with only a small constant multiple
  of additional computational expense. We illustrate the benefits of our method on
  synthetic and real oceans data.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: berlinghieri23a
month: 0
tex_title: "{G}aussian processes at the Helm(holtz): A more fluid model for ocean
  currents"
firstpage: 2113
lastpage: 2163
page: 2113-2163
order: 2113
cycles: false
bibtex_author: Berlinghieri, Renato and Trippe, Brian L. and Burt, David R. and Giordano,
  Ryan James and Srinivasan, Kaushik and \"{O}zg\"{o}kmen, Tamay and Xia, Junfei and
  Broderick, Tamara
author:
- given: Renato
  family: Berlinghieri
- given: Brian L.
  family: Trippe
- given: David R.
  family: Burt
- given: Ryan James
  family: Giordano
- given: Kaushik
  family: Srinivasan
- given: Tamay
  family: Özgökmen
- given: Junfei
  family: Xia
- given: Tamara
  family: Broderick
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
pdf: https://proceedings.mlr.press/v202/berlinghieri23a/berlinghieri23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
