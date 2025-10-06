---
title: Temporal Difference Flows
openreview: j6H7c3aQyb
abstract: Predictive models of the future are fundamental for an agent’s ability to
  reason and plan. A common strategy learns a world model and unrolls it step-by-step
  at inference, where small errors can rapidly compound. Geometric Horizon Models
  (GHMs) offer a compelling alternative by directly making predictions of future states,
  avoiding cumulative inference errors. While GHMs can be conveniently learned by
  a generative analog to temporal difference (TD) learning, existing methods are negatively
  affected by bootstrapping predictions at train time and struggle to generate high-quality
  predictions at long horizons. This paper introduces Temporal Difference Flows (TD-Flow),
  which leverages the structure of a novel Bellman equation on probability paths alongside
  flow-matching techniques to learn accurate GHMs at over 5x the horizon length of
  prior methods. Theoretically, we establish a new convergence result and primarily
  attribute TD-Flow’s efficacy to reduced gradient variance during training. We further
  show that similar arguments can be extended to diffusion-based methods. Empirically,
  we validate TD-Flow across a diverse set of domains on both generative metrics and
  downstream tasks, including policy evaluation. Moreover, integrating TD-Flow with
  recent behavior foundation models for planning over policies demonstrates substantial
  performance gains, underscoring its promise for long-horizon decision-making.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: farebrother25a
month: 0
tex_title: Temporal Difference Flows
firstpage: 16102
lastpage: 16143
page: 16102-16143
order: 16102
cycles: false
bibtex_author: Farebrother, Jesse and Pirotta, Matteo and Tirinzoni, Andrea and Munos,
  Remi and Lazaric, Alessandro and Touati, Ahmed
author:
- given: Jesse
  family: Farebrother
- given: Matteo
  family: Pirotta
- given: Andrea
  family: Tirinzoni
- given: Remi
  family: Munos
- given: Alessandro
  family: Lazaric
- given: Ahmed
  family: Touati
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/farebrother25a/farebrother25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
