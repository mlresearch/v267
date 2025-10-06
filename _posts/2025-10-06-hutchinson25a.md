---
title: Constrained Online Convex Optimization with Polyak Feasibility Steps
openreview: EAAjvpE7sp
abstract: 'In this work, we study online convex optimization with a fixed constraint
  function $g : \mathbb{R}^d \rightarrow \mathbb{R}$. Prior work on this problem has
  shown $O(\sqrt{T})$ regret and cumulative constraint satisfaction $\sum_{t=1}^{T}
  g(x_t) \leq 0$, while only accessing the constraint value and subgradient at the
  played actions $g(x_t), \partial g(x_t)$. Using the same constraint information,
  we show a stronger guarantee of anytime constraint satisfaction $g(x_t) \leq 0  \forall
  t \in [T]$, and matching $O(\sqrt{T})$ regret guarantees. These contributions are
  thanks to our approach of using Polyak feasibility steps to ensure constraint satisfaction,
  without sacrificing regret. Specifically, after each step of online gradient descent,
  our algorithm applies a subgradient descent step on the constraint function where
  the step-size is chosen according to the celebrated Polyak step-size. We further
  validate this approach with numerical experiments.'
software: https://github.com/shutch1/OCO-Polyak-Feasibility-Steps
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hutchinson25a
month: 0
tex_title: Constrained Online Convex Optimization with Polyak Feasibility Steps
firstpage: 26361
lastpage: 26375
page: 26361-26375
order: 26361
cycles: false
bibtex_author: Hutchinson, Spencer and Alizadeh, Mahnoosh
author:
- given: Spencer
  family: Hutchinson
- given: Mahnoosh
  family: Alizadeh
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/hutchinson25a/hutchinson25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
