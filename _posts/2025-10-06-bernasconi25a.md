---
title: No-Regret is not enough! Bandits with General Constraints through Adaptive
  Regret Minimization
openreview: vxM49M5B4s
abstract: In the bandits with knapsacks framework (BwK) the learner has $m$ resource-consumption
  (i.e., packing) constraints. We focus on the generalization of BwK in which the
  learner has a set of general long-term constraints. The goal of the learner is to
  maximize their cumulative reward, while at the same time achieving small cumulative
  constraints violations. In this scenario, there exist simple instances where conventional
  methods for BwK fail to yield sublinear violations of constraints. We show that
  it is possible to circumvent this issue by requiring the primal and dual algorithm
  to be weakly adaptive. Indeed, even without any information on the Slater’s parameter
  $\rho$ characterizing the problem, the interaction between weakly adaptive primal
  and dual regret minimizers leads to a “self-bounding” behavior of dual variables.
  In particular, their norm remains suitably upper bounded across the entire time
  horizon even without explicit projection steps. By exploiting this property, we
  provide best-of-both-worlds guarantees for stochastic and adversarial inputs. In
  the first case, we show that the algorithm guarantees sublinear regret. In the latter
  case, we establish a tight competitive ratio of $\rho/(1+\rho)$. In both settings,
  constraints violations are guaranteed to be sublinear in time. Finally, this results
  allow us to obtain new result for the problem of contextual bandits with linear
  constraints, providing the first no-$\alpha$-regret guarantees for adversarial contexts.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bernasconi25a
month: 0
tex_title: No-Regret is not enough! {B}andits with General Constraints through Adaptive
  Regret Minimization
firstpage: 3877
lastpage: 3898
page: 3877-3898
order: 3877
cycles: false
bibtex_author: Bernasconi, Martino and Castiglioni, Matteo and Celli, Andrea
author:
- given: Martino
  family: Bernasconi
- given: Matteo
  family: Castiglioni
- given: Andrea
  family: Celli
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/bernasconi25a/bernasconi25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
