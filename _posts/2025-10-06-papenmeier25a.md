---
title: Understanding High-Dimensional Bayesian Optimization
openreview: 1d2fpvyKvJ
abstract: Recent work reported that simple Bayesian optimization (BO) methods perform
  well for high-dimensional real-world tasks, seemingly contradicting prior work and
  tribal knowledge. This paper investigates why. We identify underlying challenges
  that arise in high-dimensional BO and explain why recent methods succeed. Our empirical
  analysis shows that vanishing gradients caused by Gaussian process (GP) initialization
  schemes play a major role in the failures of high-dimensional Bayesian optimization
  (HDBO) and that methods that promote local search behaviors are better suited for
  the task. We find that maximum likelihood estimation (MLE) of GP length scales suffices
  for state-of-the-art performance. Based on this, we propose a simple variant of
  MLE called MSR that leverages these findings to achieve state-of-the-art performance
  on a comprehensive set of real-world applications. We present targeted experiments
  to illustrate and confirm our findings.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: papenmeier25a
month: 0
tex_title: Understanding High-Dimensional {B}ayesian Optimization
firstpage: 47902
lastpage: 47923
page: 47902-47923
order: 47902
cycles: false
bibtex_author: Papenmeier, Leonard and Poloczek, Matthias and Nardi, Luigi
author:
- given: Leonard
  family: Papenmeier
- given: Matthias
  family: Poloczek
- given: Luigi
  family: Nardi
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/papenmeier25a/papenmeier25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
