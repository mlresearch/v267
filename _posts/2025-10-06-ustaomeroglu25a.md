---
title: 'A Theoretical Study of (Hyper) Self-Attention through the Lens of Interactions:
  Representation, Training, Generalization'
openreview: wQvR1LHboD
abstract: Self-attention has emerged as a core component of modern neural architectures,
  yet its theoretical underpinnings remain elusive. In this paper, we study self-attention
  through the lens of <em>interacting entities</em>, ranging from agents in multi-agent
  reinforcement learning to alleles in genetic sequences, and show that a single layer
  linear self-attention can <em>efficiently</em> represent, learn, and generalize
  functions capturing pairwise interactions, including out-of-distribution scenarios.
  Our analysis reveals that self-attention acts as a <em>mutual interaction learner</em>
  under minimal assumptions on the diversity of interaction patterns observed during
  training, thereby encompassing a wide variety of real-world domains. In addition,
  we validate our theoretical insights through experiments demonstrating that self-attention
  learns interaction functions and generalizes across both population distributions
  and out-of-distribution scenarios. Building on our theories, we introduce <em>HyperFeatureAttention</em>,
  a novel neural network module designed to learn couplings of different feature-level
  interactions between entities. Furthermore, we propose <em>HyperAttention</em>,
  a new module that extends beyond pairwise interactions to capture multi-entity dependencies,
  such as three-way, four-way, or general $n$-way interactions.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ustaomeroglu25a
month: 0
tex_title: 'A Theoretical Study of ({H}yper) Self-Attention through the Lens of Interactions:
  Representation, Training, Generalization'
firstpage: 60657
lastpage: 60710
page: 60657-60710
order: 60657
cycles: false
bibtex_author: Ustaomeroglu, Muhammed and Qu, Guannan
author:
- given: Muhammed
  family: Ustaomeroglu
- given: Guannan
  family: Qu
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/ustaomeroglu25a/ustaomeroglu25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
