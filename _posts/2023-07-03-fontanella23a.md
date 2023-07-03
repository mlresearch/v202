---
title: 'ACAT: Adversarial Counterfactual Attention for Classification and Detection
  in Medical Imaging'
openreview: yrVIUwRtzy
abstract: In some medical imaging tasks and other settings where only small parts
  of the image are informative for the classification task, traditional CNNs can sometimes
  struggle to generalise. Manually annotated Regions of Interest (ROI) are often used
  to isolate the most informative parts of the image. However, these are expensive
  to collect and may vary significantly across annotators. To overcome these issues,
  we propose a framework that employs saliency maps to obtain soft spatial attention
  masks that modulate the image features at different scales. We refer to our method
  as <em>Adversarial Counterfactual Attention</em> (ACAT). ACAT increases the baseline
  classification accuracy of lesions in brain CT scans from $71.39 %$ to $72.55 %$
  and of COVID-19 related findings in lung CT scans from $67.71 %$ to $70.84 %$ and
  exceeds the performance of competing methods. We investigate the best way to generate
  the saliency maps employed in our architecture and propose a way to obtain them
  from adversarially generated counterfactual images. They are able to isolate the
  area of interest in brain and lung CT scans without using any manual annotations.
  In the task of localising the lesion location out of 6 possible regions, they obtain
  a score of $65.05 %$ on brain CT scans, improving the score of $61.29 %$ obtained
  with the best competing method.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: fontanella23a
month: 0
tex_title: "{ACAT}: Adversarial Counterfactual Attention for Classification and Detection
  in Medical Imaging"
firstpage: 10153
lastpage: 10169
page: 10153-10169
order: 10153
cycles: false
bibtex_author: Fontanella, Alessandro and Antoniou, Antreas and Li, Wenwen and Wardlaw,
  Joanna and Mair, Grant and Trucco, Emanuele and Storkey, Amos
author:
- given: Alessandro
  family: Fontanella
- given: Antreas
  family: Antoniou
- given: Wenwen
  family: Li
- given: Joanna
  family: Wardlaw
- given: Grant
  family: Mair
- given: Emanuele
  family: Trucco
- given: Amos
  family: Storkey
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
pdf: https://proceedings.mlr.press/v202/fontanella23a/fontanella23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
