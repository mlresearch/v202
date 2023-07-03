---
title: Global Context Vision Transformers
openreview: 75k3jJqAnm
abstract: We propose global context vision transformer (GC ViT), a novel architecture
  that enhances parameter and compute utilization for computer vision. Our method
  leverages global context self-attention modules, joint with standard local self-attention,
  to effectively and efficiently model both long and short-range spatial interactions,
  without the need for expensive operations such as computing attention masks or shifting
  local windows. In addition, we address the lack of the inductive bias in ViTs, and
  propose to leverage a modified fused inverted residual blocks in our architecture.
  Our proposed GC ViT achieves state-of-the-art results across image classification,
  object detection and semantic segmentation tasks. On ImageNet-1K dataset for classification,
  the variants of GC ViT with 51M, 90M and 201M parameters achieve 84.3%, 85.0% and
  85.7% Top-1 accuracy, respectively, at 224 image resolution and without any pre-training,
  hence surpassing comparably-sized prior art such as CNN-based ConvNeXt and ViT-based
  MaxViT and Swin Transformer by a large margin. Pre-trained GC ViT backbones in downstream
  tasks of object detection, instance segmentation, and semantic segmentation using
  MS COCO and ADE20K datasets outperform prior work consistently. Specifically, GC
  ViT with a 4-scale DINO detection head achieves a box AP of 58.3 on MS COCO dataset.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hatamizadeh23a
month: 0
tex_title: Global Context Vision Transformers
firstpage: 12633
lastpage: 12646
page: 12633-12646
order: 12633
cycles: false
bibtex_author: Hatamizadeh, Ali and Yin, Hongxu and Heinrich, Greg and Kautz, Jan
  and Molchanov, Pavlo
author:
- given: Ali
  family: Hatamizadeh
- given: Hongxu
  family: Yin
- given: Greg
  family: Heinrich
- given: Jan
  family: Kautz
- given: Pavlo
  family: Molchanov
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
pdf: https://proceedings.mlr.press/v202/hatamizadeh23a/hatamizadeh23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
