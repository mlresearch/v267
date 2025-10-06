---
title: Learning Gaussian DAG Models without Condition Number Bounds
openreview: fxmJHFscQz
abstract: We study the problem of learning the topology of a directed Gaussian Graphical
  Model under the equal-variance assumption, where the graph has $n$ nodes and maximum
  in-degree $d$. Prior work has established that $O(d \log n)$ samples are sufficient
  for this task. However, an important factor that is often overlooked in these analyses
  is the dependence on the condition number of the covariance matrix of the model.
  Indeed, all algorithms from prior work require a number of samples that grows polynomially
  with this condition number. In many cases this is unsatisfactory, since the condition
  number could grow polynomially with $n$, rendering these prior approaches impractical
  in high-dimensional settings. In this work, we provide an algorithm that recovers
  the underlying graph and prove that the number of samples required is independent
  of the condition number. Furthermore, we establish lower bounds that nearly match
  the upper bound up to a $d$-factor, thus providing an almost tight characterization
  of the true sample complexity of the problem. Moreover, under a further assumption
  that all the variances of the variables are bounded, we design a polynomial-time
  algorithm that recovers the underlying graph, at the cost of an additional polynomial
  dependence of the sample complexity on $d$. We complement our theoretical findings
  with simulations on synthetic datasets that confirm our predictions.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: daskalakis25a
month: 0
tex_title: Learning {G}aussian {DAG} Models without Condition Number Bounds
firstpage: 12554
lastpage: 12589
page: 12554-12589
order: 12554
cycles: false
bibtex_author: Daskalakis, Constantinos Costis and Kandiros, Anthimos Vardis and Yao,
  Rui
author:
- given: Constantinos Costis
  family: Daskalakis
- given: Anthimos Vardis
  family: Kandiros
- given: Rui
  family: Yao
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/daskalakis25a/daskalakis25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
