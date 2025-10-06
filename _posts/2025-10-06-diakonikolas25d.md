---
title: On Fine-Grained Distinct Element Estimation
openreview: J1xVXyWv2T
abstract: We study the problem of distributed distinct element estimation, where $\alpha$
  servers each receive a subset of a universe $[n]$ and aim to compute a $(1+\varepsilon)$-approximation
  to the number of distinct elements using minimal communication. While prior work
  establishes a worst-case bound of $\Theta\left(\alpha\log n+\frac{\alpha}{\varepsilon^2}\right)$
  bits, these results rely on assumptions that may not hold in practice. We introduce
  a new parameterization based on the number $C = \frac{\beta}{\varepsilon^2}$ of
  pairwise collisions, i.e., instances where the same element appears on multiple
  servers, and design a protocol that uses only $O\left(\alpha\log n\log\log n+\frac{\sqrt{\beta}}{\varepsilon^2}
  \log n\right)$ bits, breaking previous lower bounds when $C$ is small. We further
  improve our algorithm under assumptions on the number of distinct elements or collisions
  and provide matching lower bounds in all regimes, establishing $C$ as a tight complexity
  measure for the problem. Finally, we consider streaming algorithms for distinct
  element estimation parameterized by the number of items with frequency larger than
  $1$. Overall, our results offer insight into why statistical problems with known
  hardness results can be efficiently solved in practice.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: diakonikolas25d
month: 0
tex_title: On Fine-Grained Distinct Element Estimation
firstpage: 13643
lastpage: 13678
page: 13643-13678
order: 13643
cycles: false
bibtex_author: Diakonikolas, Ilias and Kane, Daniel and Lee, Jasper C.H. and Pittas,
  Thanasis and Woodruff, David and Zhou, Samson
author:
- given: Ilias
  family: Diakonikolas
- given: Daniel
  family: Kane
- given: Jasper C.H.
  family: Lee
- given: Thanasis
  family: Pittas
- given: David
  family: Woodruff
- given: Samson
  family: Zhou
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/diakonikolas25d/diakonikolas25d.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
