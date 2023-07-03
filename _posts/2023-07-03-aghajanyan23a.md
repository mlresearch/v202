---
title: Scaling Laws for Generative Mixed-Modal Language Models
openreview: 2n7dHVhwJf
abstract: Generative language models define distributions over sequences of tokens
  that can represent essentially any combination of data modalities (e.g., any permutation
  of image tokens from VQ-VAEs, speech tokens from HuBERT, BPE tokens for language
  or code, and so on). To better understand the scaling properties of such mixed-modal
  models, we conducted over 250 experiments using seven different modalities and model
  sizes ranging from 8 million to 30 billion, trained on 5-100 billion tokens. We
  report new mixed-modal scaling laws that unify the contributions of individual modalities
  and the interactions between them. Specifically, we explicitly model the optimal
  synergy and competition due to data and model size as an additive term to previous
  uni-modal scaling laws. We also find four empirical phenomena observed during the
  training, such as emergent coordinate-ascent style training that naturally alternates
  between modalities, guidelines for selecting critical hyper-parameters, and connections
  between mixed-modal competition and training stability. Finally, we test our scaling
  law by training a 30B speech-text model, which significantly outperforms the corresponding
  unimodal models. Overall, our research provides valuable insights into the design
  and training of mixed-modal generative models, an important new class of unified
  models that have unique distributional properties.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: aghajanyan23a
month: 0
tex_title: Scaling Laws for Generative Mixed-Modal Language Models
firstpage: 265
lastpage: 279
page: 265-279
order: 265
cycles: false
bibtex_author: Aghajanyan, Armen and Yu, Lili and Conneau, Alexis and Hsu, Wei-Ning
  and Hambardzumyan, Karen and Zhang, Susan and Roller, Stephen and Goyal, Naman and
  Levy, Omer and Zettlemoyer, Luke
author:
- given: Armen
  family: Aghajanyan
- given: Lili
  family: Yu
- given: Alexis
  family: Conneau
- given: Wei-Ning
  family: Hsu
- given: Karen
  family: Hambardzumyan
- given: Susan
  family: Zhang
- given: Stephen
  family: Roller
- given: Naman
  family: Goyal
- given: Omer
  family: Levy
- given: Luke
  family: Zettlemoyer
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
pdf: https://proceedings.mlr.press/v202/aghajanyan23a/aghajanyan23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
