---
title: Competitively Consistent Clustering
openreview: x2xZidAK4J
abstract: In <em>fully-dynamic consistent clustering</em>, we are given a finite metric
  space $(M,d)$, and a set $F\subseteq M$ of possible locations for opening centers.
  Data points arrive and depart, and the goal is to maintain an approximately optimal
  clustering solution at all times while minimizing the <em>recourse</em>, the total
  number of additions/deletions of centers over time. Specifically, we study fully
  dynamic versions of the classical $k$-center, facility location, and $k$-median
  problems. We design algorithms that, given a parameter $\beta\geq 1$, maintain an
  $O(\beta)$-approximate solution at all times, and whose total recourse is bounded
  by $O(\log |F| \log \Delta) \cdot OPT_{rec}^{\beta}$. Here $OPT_{rec}^{\beta}$ is
  the minimal recourse of an offline algorithm that maintains a $\beta$-approximate
  solution at all times, and $\Delta$ is the metric aspect ratio. We obtain our results
  via a reduction to the recently proposed <em>Positive Body Chasing</em> framework
  of [Bhattacharya Buchbinder Levin Saranurak, FOCS 2023], which we show gives fractional
  solutions to our clustering problems online. Our contribution is to round these
  fractional solutions while preserving the approximation and recourse guarantees.
  We complement our positive results with logarithmic lower bounds which show that
  our bounds are nearly tight.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: buchbinder25a
month: 0
tex_title: Competitively Consistent Clustering
firstpage: 5793
lastpage: 5810
page: 5793-5810
order: 5793
cycles: false
bibtex_author: Buchbinder, Niv and Levin, Roie and Yang, Yue
author:
- given: Niv
  family: Buchbinder
- given: Roie
  family: Levin
- given: Yue
  family: Yang
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/buchbinder25a/buchbinder25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
