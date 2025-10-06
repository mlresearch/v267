---
title: On Learning Parallel Pancakes with Mostly Uniform Weights
openreview: jNCTdUsQaC
abstract: We study the complexity of learning $k$-mixtures of Gaussians ($k$-GMMs)
  on $\mathbb R^d$. This task is known to have complexity $d^{\Omega(k)}$ in full
  generality. To circumvent this exponential lower bound on the number of components,
  research has focused on learning families of GMMs satisfying additional structural
  properties. A natural assumption posits that the component weights are not exponentially
  small and that the components have the same unknown covariance. Recent work gave
  a $d^{O(\log(1/w_{\min}))}$-time algorithm for this class of GMMs, where $w_{\min}$
  is the minimum weight. Our first main result is a Statistical Query (SQ) lower bound
  showing that this quasi-polynomial upper bound is essentially best possible, even
  for the special case of uniform weights. Specifically, we show that it is SQ-hard
  to distinguish between such a mixture and the standard Gaussian. We further explore
  how the distribution of weights affects the complexity of this task. Our second
  main result is a quasi-polynomial upper bound for the aforementioned testing task
  when most of the weights are uniform while a small fraction of the weights are potentially
  arbitrary.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: diakonikolas25b
month: 0
tex_title: On Learning Parallel Pancakes with Mostly Uniform Weights
firstpage: 13601
lastpage: 13621
page: 13601-13621
order: 13601
cycles: false
bibtex_author: Diakonikolas, Ilias and Kane, Daniel and Karmalkar, Sushrut and Lee,
  Jasper C.H. and Pittas, Thanasis
author:
- given: Ilias
  family: Diakonikolas
- given: Daniel
  family: Kane
- given: Sushrut
  family: Karmalkar
- given: Jasper C.H.
  family: Lee
- given: Thanasis
  family: Pittas
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/diakonikolas25b/diakonikolas25b.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
