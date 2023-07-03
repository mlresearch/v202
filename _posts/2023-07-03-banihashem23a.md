---
title: Dynamic Constrained Submodular Optimization with Polylogarithmic Update Time
openreview: 2hF9MnBfUk
abstract: Maximizing a monotone submodular function under cardinality constraint $k$
  is a core problem in machine learning and database with many basic applications,
  including video and data summarization, recommendation systems, feature extraction,
  exemplar clustering, and coverage problems. We study this classic problem in the
  fully dynamic model where a stream of insertions and deletions of elements of an
  underlying ground set is given and the goal is to maintain an approximate solution
  using a fast update time. A recent paper at NeurIPS’20 by Lattanzi, Mitrovic, Norouzi-Fard,
  Tarnawski, Zadimoghaddam claims to obtain a dynamic algorithm for this problem with
  a $(\frac{1}{2} -\epsilon)$ approximation ratio and a query complexity bounded by
  $\mathrm{poly}(\log(n),\log(k),\epsilon^{-1})$. However, as we explain in this paper,
  the analysis has some important gaps. Having a dynamic algorithm for the problem
  with polylogarithmic update time is even more important in light of a recent result
  by Chen and Peng at STOC’22 who show a matching lower bound for the problem – any
  randomized algorithm with a $\frac{1}{2}+\epsilon$ approximation ratio must have
  an amortized query complexity that is polynomial in $n$. In this paper, we develop
  a simpler algorithm for the problem that maintains a $(\frac{1}{2}-\epsilon)$-approximate
  solution for submodular maximization under cardinality constraint $k$ using a polylogarithmic
  amortized update time.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: banihashem23a
month: 0
tex_title: Dynamic Constrained Submodular Optimization with Polylogarithmic Update
  Time
firstpage: 1660
lastpage: 1691
page: 1660-1691
order: 1660
cycles: false
bibtex_author: Banihashem, Kiarash and Biabani, Leyla and Goudarzi, Samira and Hajiaghayi,
  Mohammadtaghi and Jabbarzade, Peyman and Monemizadeh, Morteza
author:
- given: Kiarash
  family: Banihashem
- given: Leyla
  family: Biabani
- given: Samira
  family: Goudarzi
- given: Mohammadtaghi
  family: Hajiaghayi
- given: Peyman
  family: Jabbarzade
- given: Morteza
  family: Monemizadeh
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
pdf: https://proceedings.mlr.press/v202/banihashem23a/banihashem23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
