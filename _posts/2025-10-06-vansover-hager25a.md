---
title: Rapid Overfitting of Multi-Pass SGD in Stochastic Convex Optimization
openreview: Qq5h78Eshy
abstract: We study the out-of-sample performance of multi-pass stochastic gradient
  descent (SGD) in the fundamental stochastic convex optimization (SCO) model. While
  one-pass SGD is known to achieve an optimal $\Theta(1/\sqrt{n})$ excess population
  loss given a sample of size $n$, much less is understood about the multi-pass version
  of the algorithm which is widely used in practice. Somewhat surprisingly, we show
  that in the general non-smooth case of SCO, just a few epochs of SGD can already
  hurt its out-of-sample performance significantly and lead to overfitting. In particular,
  using a step size $\eta = \Theta(1/\sqrt{n})$, which gives the optimal rate after
  one pass, can lead to population loss as large as $\Omega(1)$ after just one additional
  pass. More generally, we show that the population loss from the second pass onward
  is of the order $\Theta(1/(\eta T) + \eta \sqrt{T})$, where $T$ is the total number
  of steps. These results reveal a certain phase-transition in the out-of-sample behavior
  of SGD after the first epoch, as well as a sharp separation between the rates of
  overfitting in the smooth and non-smooth cases of SCO. Additionally, we extend our
  results to with-replacement SGD, proving that the same asymptotic bounds hold after
  $O(n \log n)$ steps. Finally, we also prove a lower bound of $\Omega(\eta \sqrt{n})$
  on the generalization gap of one-pass SGD in dimension $d = {\widetilde O}(n)$,
  improving on recent results of Koren et al. (2022) and Schliserman et al. (2024).
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: vansover-hager25a
month: 0
tex_title: Rapid Overfitting of Multi-Pass {SGD} in Stochastic Convex Optimization
firstpage: 60905
lastpage: 60923
page: 60905-60923
order: 60905
cycles: false
bibtex_author: Vansover-Hager, Shira and Koren, Tomer and Livni, Roi
author:
- given: Shira
  family: Vansover-Hager
- given: Tomer
  family: Koren
- given: Roi
  family: Livni
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/vansover-hager25a/vansover-hager25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
