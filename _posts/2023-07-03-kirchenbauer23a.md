---
title: A Watermark for Large Language Models
openreview: aX8ig9X2a7
abstract: Potential harms of large language models can be mitigated by watermarking
  model output, i.e., embedding signals into generated text that are invisible to
  humans but algorithmically detectable from a short span of tokens. We propose a
  watermarking framework for proprietary language models. The watermark can be embedded
  with negligible impact on text quality, and can be detected using an efficient open-source
  algorithm without access to the language model API or parameters. The watermark
  works by selecting a randomized set of "green" tokens before a word is generated,
  and then softly promoting use of green tokens during sampling. We propose a statistical
  test for detecting the watermark with interpretable p-values, and derive an information-theoretic
  framework for analyzing the sensitivity of the watermark. We test the watermark
  using a multi-billion parameter model from the Open Pretrained Transformer (OPT)
  family, and discuss robustness and security.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kirchenbauer23a
month: 0
tex_title: A Watermark for Large Language Models
firstpage: 17061
lastpage: 17084
page: 17061-17084
order: 17061
cycles: false
bibtex_author: Kirchenbauer, John and Geiping, Jonas and Wen, Yuxin and Katz, Jonathan
  and Miers, Ian and Goldstein, Tom
author:
- given: John
  family: Kirchenbauer
- given: Jonas
  family: Geiping
- given: Yuxin
  family: Wen
- given: Jonathan
  family: Katz
- given: Ian
  family: Miers
- given: Tom
  family: Goldstein
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
pdf: https://proceedings.mlr.press/v202/kirchenbauer23a/kirchenbauer23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
