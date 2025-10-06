---
title: The Polynomial Stein Discrepancy for Assessing Moment Convergence
openreview: 2QaqxseJYT
abstract: We propose a novel method for measuring the discrepancy between a set of
  samples and a desired posterior distribution for Bayesian inference. Classical methods
  for assessing sample quality like the effective sample size are not appropriate
  for scalable Bayesian sampling algorithms, such as stochastic gradient Langevin
  dynamics, that are asymptotically biased. Instead, the gold standard is to use the
  kernel Stein Discrepancy (KSD), which is itself not scalable given its quadratic
  cost in the number of samples. The KSD and its faster extensions also typically
  suffer from the curse-of-dimensionality and can require extensive tuning. To address
  these limitations, we develop the polynomial Stein discrepancy (PSD) and an associated
  goodness-of-fit test. While the new test is not fully convergence-determining, we
  prove that it detects differences in the first $r$ moments for Gaussian targets.
  We empirically show that the test has higher power than its competitors in several
  examples, and at a lower computational cost. Finally, we demonstrate that the PSD
  can assist practitioners to select hyper-parameters of Bayesian sampling algorithms
  more efficiently than competitors.
software: https://github.com/Nars98/PSD
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: srinivasan25a
month: 0
tex_title: The Polynomial Stein Discrepancy for Assessing Moment Convergence
firstpage: 56820
lastpage: 56842
page: 56820-56842
order: 56820
cycles: false
bibtex_author: Srinivasan, Narayan and Sutton, Matthew and Drovandi, Christopher and
  South, Leah F
author:
- given: Narayan
  family: Srinivasan
- given: Matthew
  family: Sutton
- given: Christopher
  family: Drovandi
- given: Leah F
  family: South
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/srinivasan25a/srinivasan25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
