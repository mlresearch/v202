---
title: 'SpotEM: Efficient Video Search for Episodic Memory'
openreview: vOcOzRWpvm
abstract: 'The goal in episodic memory (EM) is to search a long egocentric video to
  answer a natural language query (e.g., “where did I leave my purse?”). Existing
  EM methods exhaustively extract expensive fixed-length clip features to look everywhere
  in the video for the answer, which is infeasible for long wearable-camera videos
  that span hours or even days. We propose SpotEM, an approach to achieve efficiency
  for a given EM method while maintaining good accuracy. SpotEM consists of three
  key ideas: 1) a novel clip selector that learns to identify promising video regions
  to search conditioned on the language query; 2) a set of low-cost semantic indexing
  features that capture the context of rooms, objects, and interactions that suggest
  where to look; and 3) distillation losses that address the optimization issues arising
  from end-to-end joint training of the clip selector and EM model. Our experiments
  on 200+ hours of video from the Ego4D EM Natural Language Queries benchmark and
  three different EM models demonstrate the effectiveness of our approach: computing
  only 10% – 25% of the clip features, we preserve 84% – 97% of the original EM model’s
  accuracy. Project page: https://vision.cs.utexas.edu/projects/spotem'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ramakrishnan23a
month: 0
tex_title: "{S}pot{EM}: Efficient Video Search for Episodic Memory"
firstpage: 28618
lastpage: 28636
page: 28618-28636
order: 28618
cycles: false
bibtex_author: Ramakrishnan, Santhosh Kumar and Al-Halah, Ziad and Grauman, Kristen
author:
- given: Santhosh Kumar
  family: Ramakrishnan
- given: Ziad
  family: Al-Halah
- given: Kristen
  family: Grauman
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
pdf: https://proceedings.mlr.press/v202/ramakrishnan23a/ramakrishnan23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
