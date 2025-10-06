---
title: Batch List-Decodable Linear Regression via Higher Moments
openreview: Vx7YaE7vJU
abstract: We study the task of list-decodable linear regression using batches, recently
  introduced by Das et al. 2023.. In this setting, we are given $m$ batches with each
  batch containing $n$ points in $\mathbb R^d$. A batch is called clean if the points
  it contains are i.i.d. samples from an unknown linear regression distribution. For
  a parameter $\alpha \in (0, 1/2)$, an unknown $\alpha$-fraction of the batches are
  clean and no assumptions are made on the remaining batches. The goal is to output
  a small list of vectors at least one of which is close to the true regressor vector
  in $\ell_2$-norm. Das et al. 2023 gave an efficient algorithm for this task, under
  natural distributional assumptions, with the following guarantee. Under the assumption
  that the batch size satisfies $n \geq \tilde{\Omega}(\alpha^{-1})$ and the total
  number of batches is $m = \text{poly}(d, n, 1/\alpha)$, their algorithm runs in
  polynomial time and outputs a list of $O(1/\alpha^2)$ vectors at least one of which
  is $\tilde{O}(\alpha^{-1/2}/\sqrt{n})$ close to the target regressor. Here we design
  a new polynomial-time algorithm for this task with significantly stronger guarantees
  under the assumption that the low-degree moments of the covariates distribution
  are Sum-of-Squares (SoS) certifiably bounded. Specifically, for any constant $\delta>0$,
  as long as the batch size is $n \geq \Omega_{\delta}(\alpha^{-\delta})$ and the
  degree-$\Theta(1/\delta)$ moments of the covariates are SoS certifiably bounded,
  our algorithm uses $m = \text{poly}((dn)^{1/\delta}, 1/\alpha)$ batches, runs in
  polynomial-time, and outputs an $O(1/\alpha)$-sized list of vectors one of which
  is $O(\alpha^{-\delta/2}/\sqrt{n})$ close to the target. That is, our algorithm
  substantially improves both the minimum batch size and the final error guarantee,
  while achieving the optimal list size. Our approach leverages higher-order moment
  information by carefully combining the SoS paradigm interleaved with an iterative
  method and a novel list pruning procedure for this setting. In the process, we give
  an SoS proof of the Marcinkiewicz-Zygmund inequality that may be of broader applicability.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: diakonikolas25c
month: 0
tex_title: Batch List-Decodable Linear Regression via Higher Moments
firstpage: 13622
lastpage: 13642
page: 13622-13642
order: 13622
cycles: false
bibtex_author: Diakonikolas, Ilias and Kane, Daniel and Karmalkar, Sushrut and Liu,
  Sihan and Pittas, Thanasis
author:
- given: Ilias
  family: Diakonikolas
- given: Daniel
  family: Kane
- given: Sushrut
  family: Karmalkar
- given: Sihan
  family: Liu
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/diakonikolas25c/diakonikolas25c.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
