---
title: Solving Zero-Sum Convex Markov Games
openreview: dSJo5X56KQ
abstract: We contribute the first provable guarantees of global convergence to Nash
  equilibria (NE) in two-player zero-sum convex Markov games (cMGs) by using independent
  policy gradient methods. Convex Markov games, recently defined by Gemp et al.(2024),
  extend Markov decision processes to multi-agent settings with preferences that are
  convex over occupancy measures, offering a broad framework for modeling generic
  strategic interactions. However, even the fundamental min-max case of cMGs presents
  significant challenges, including inherent nonconvexity, the absence of Bellman
  consistency, and the complexity of the infinite horizon. Our results follow a two-step
  approach. First, leveraging properties of hidden-convex–hidden-concave functions,
  we show that a simple nonconvex regularization transforms the min-max optimization
  problem into a nonconvex–proximal Polyak-{Ł}ojasiewicz (NC-pPL) objective. Crucially,
  this regularization can stabilize the iterates of independent policy gradient methods
  and ultimately lead them to converge to equilibria. Second, building on this reduction,
  we address the general constrained min-max problems under NC-pPL and two-sided pPL
  conditions, providing the first global convergence guarantees for stochastic nested
  and alternating gradient descent-ascent methods, which we believe may be of independent
  interest.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kalogiannis25a
month: 0
tex_title: Solving Zero-Sum Convex {M}arkov Games
firstpage: 28735
lastpage: 28794
page: 28735-28794
order: 28735
cycles: false
bibtex_author: Kalogiannis, Fivos and Vlatakis-Gkaragkounis, Emmanouil-Vasileios and
  Gemp, Ian and Piliouras, Georgios
author:
- given: Fivos
  family: Kalogiannis
- given: Emmanouil-Vasileios
  family: Vlatakis-Gkaragkounis
- given: Ian
  family: Gemp
- given: Georgios
  family: Piliouras
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/kalogiannis25a/kalogiannis25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
