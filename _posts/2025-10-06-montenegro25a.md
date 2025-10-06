---
title: Convergence Analysis of Policy Gradient Methods with Dynamic Stochasticity
openreview: XEYoTQv00G
abstract: "<em>Policy gradient</em> (PG) methods are effective <em>reinforcement learning</em>
  (RL) approaches, particularly for continuous problems. While they optimize stochastic
  (hyper)policies via action- or parameter-space exploration, real-world applications
  often require deterministic policies. Existing PG convergence guarantees to deterministic
  policies assume a fixed stochasticity in the (hyper)policy, tuned according to the
  desired final suboptimality, whereas practitioners commonly use a dynamic stochasticity
  level. This work provides the theoretical foundations for this practice. We introduce
  PES, a phase-based method that reduces stochasticity via a deterministic schedule
  while running PG subroutines with fixed stochasticity in each phase. Under gradient
  domination assumptions, PES achieves last-iterate convergence to the optimal deterministic
  policy with a sample complexity of order $\\widetilde{\\mathcal{O}}(\\epsilon^{-5})$.
  Additionally, we analyze the common practice, termed SL-PG, of jointly learning
  stochasticity (via an appropriate parameterization) and (hyper)policy parameters.
  We show that SL-PG also ensures last-iterate convergence with a rate $\\widetilde{\\mathcal{O}}(\\epsilon^{-3})$,
  but to the optimal stochastic (hyper)policy only, requiring stronger assumptions
  compared to PES."
software: https://github.com/MontenegroAlessandro/MagicRL
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: montenegro25a
month: 0
tex_title: Convergence Analysis of Policy Gradient Methods with Dynamic Stochasticity
firstpage: 44652
lastpage: 44698
page: 44652-44698
order: 44652
cycles: false
bibtex_author: Montenegro, Alessandro and Mussi, Marco and Papini, Matteo and Metelli,
  Alberto Maria
author:
- given: Alessandro
  family: Montenegro
- given: Marco
  family: Mussi
- given: Matteo
  family: Papini
- given: Alberto Maria
  family: Metelli
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/montenegro25a/montenegro25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
