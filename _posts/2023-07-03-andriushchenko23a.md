---
title: A Modern Look at the Relationship between Sharpness and Generalization
openreview: VZp9X410D3
abstract: Sharpness of minima is a promising quantity that can correlate with generalization
  in deep networks and, when optimized during training, can improve generalization.
  However, standard sharpness is not invariant under reparametrizations of neural
  networks, and, to fix this, reparametrization-invariant sharpness definitions have
  been proposed, most prominently adaptive sharpness (Kwon et al., 2021). But does
  it really capture generalization in modern practical settings? We comprehensively
  explore this question in a detailed study of various definitions of adaptive sharpness
  in settings ranging from training from scratch on ImageNet and CIFAR-10 to fine-tuning
  CLIP on ImageNet and BERT on MNLI. We focus mostly on transformers for which little
  is known in terms of sharpness despite their widespread usage. Overall, we observe
  that sharpness does not correlate well with generalization but rather with some
  training parameters like the learning rate that can be positively or negatively
  correlated with generalization depending on the setup. Interestingly, in multiple
  cases, we observe a consistent negative correlation of sharpness with OOD generalization
  implying that sharper minima can generalize better. Finally, we illustrate on a
  simple model that the right sharpness measure is highly data-dependent, and that
  we do not understand well this aspect for realistic data distributions.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: andriushchenko23a
month: 0
tex_title: A Modern Look at the Relationship between Sharpness and Generalization
firstpage: 840
lastpage: 902
page: 840-902
order: 840
cycles: false
bibtex_author: Andriushchenko, Maksym and Croce, Francesco and M\"{u}ller, Maximilian
  and Hein, Matthias and Flammarion, Nicolas
author:
- given: Maksym
  family: Andriushchenko
- given: Francesco
  family: Croce
- given: Maximilian
  family: Müller
- given: Matthias
  family: Hein
- given: Nicolas
  family: Flammarion
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
pdf: https://proceedings.mlr.press/v202/andriushchenko23a/andriushchenko23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
