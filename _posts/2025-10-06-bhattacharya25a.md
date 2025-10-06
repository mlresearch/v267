---
title: Almost Optimal Fully Dynamic $k$-Center Clustering with Recourse
openreview: RmZZ4AeNsl
abstract: In this paper, we consider the <em>metric $k$-center</em> problem in the
  fully dynamic setting, where we are given a metric space $(V,d)$ evolving via a
  sequence of point insertions and deletions and our task is to maintain a subset
  $S \subseteq V$ of at most $k$ points that minimizes the objective $\max_{x \in
  V} \min_{y \in S}d(x, y)$. We want to design our algorithm so that we minimize its
  <em>approximation ratio</em>, <em>recourse</em> (the number of changes it makes
  to the solution $S$) and <em>update time</em> (the time it takes to handle an update).
  We give a simple algorithm for dynamic $k$-center that maintains a $O(1)$-approximate
  solution with $O(1)$ amortized recourse and $\tilde O(k)$ amortized update time,
  <em>obtaining near-optimal approximation, recourse and update time simultaneously</em>.
  We obtain our result by combining a variant of the dynamic $k$-center algorithm
  of Bateni et al. [SODA’23] with the dynamic sparsifier of Bhattacharya et al. [NeurIPS’23].
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bhattacharya25a
month: 0
tex_title: Almost Optimal Fully Dynamic $k$-Center Clustering with Recourse
firstpage: 4196
lastpage: 4209
page: 4196-4209
order: 4196
cycles: false
bibtex_author: Bhattacharya, Sayan and Costa, Martin and Farokhnejad, Ermiya and Lattanzi,
  Silvio and Parotsidis, Nikos
author:
- given: Sayan
  family: Bhattacharya
- given: Martin
  family: Costa
- given: Ermiya
  family: Farokhnejad
- given: Silvio
  family: Lattanzi
- given: Nikos
  family: Parotsidis
date: 2025-10-06
address:
container-title: Proceedings of the 42nd International Conference on Machine Learning
volume: '267'
genre: inproceedings
issued:
  date-parts:
  - 2025
  - 10
  - 6
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/bhattacharya25a/bhattacharya25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
