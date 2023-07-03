---
title: When does Privileged information Explain Away Label Noise?
openreview: CnHxxjqkMi
abstract: Leveraging privileged information (PI), or features available during training
  but not at test time, has recently been shown to be an effective method for addressing
  label noise. However, the reasons for its effectiveness are not well understood.
  In this study, we investigate the role played by different properties of the PI
  in explaining away label noise. Through experiments on multiple datasets with real
  PI (CIFAR-N/H) and a new large-scale benchmark ImageNet-PI, we find that PI is most
  helpful when it allows networks to easily distinguish clean from noisy data, while
  enabling a learning shortcut to memorize the noisy examples. Interestingly, when
  PI becomes too predictive of the target label, PI methods often perform worse than
  their no-PI baselines. Based on these findings, we propose several enhancements
  to the state-of-the-art PI methods and demonstrate the potential of PI as a means
  of tackling label noise. Finally, we show how we can easily combine the resulting
  PI approaches with existing no-PI techniques designed to deal with label noise.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ortiz-jimenez23a
month: 0
tex_title: When does Privileged information Explain Away Label Noise?
firstpage: 26646
lastpage: 26669
page: 26646-26669
order: 26646
cycles: false
bibtex_author: Ortiz-Jimenez, Guillermo and Collier, Mark and Nawalgaria, Anant and
  D'Amour, Alexander Nicholas and Berent, Jesse and Jenatton, Rodolphe and Kokiopoulou,
  Efi
author:
- given: Guillermo
  family: Ortiz-Jimenez
- given: Mark
  family: Collier
- given: Anant
  family: Nawalgaria
- given: Alexander Nicholas
  family: D’Amour
- given: Jesse
  family: Berent
- given: Rodolphe
  family: Jenatton
- given: Efi
  family: Kokiopoulou
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
pdf: https://proceedings.mlr.press/v202/ortiz-jimenez23a/ortiz-jimenez23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
