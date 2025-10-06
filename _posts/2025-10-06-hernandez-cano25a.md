---
title: Neurosymbolic World Models for Sequential Decision Making
openreview: qkeYxpB9w0
abstract: We present Structured World Modeling for Policy Optimization (SWMPO), a
  framework for unsupervised learning of neurosymbolic Finite State Machines (FSM)
  that capture environmental structure for policy optimization. Traditional unsupervised
  world modeling methods rely on unstructured representations, such as neural networks,
  that do not explicitly represent high-level patterns within the system (e.g., patterns
  in the dynamics of regions such as <em>water</em> and <em>land</em>). Instead, SWMPO
  models the environment as a finite state machine (FSM), where each state corresponds
  to a specific region with distinct dynamics. This structured representation can
  then be leveraged for tasks like policy optimization. Previous works that synthesize
  FSMs for this purpose have been limited to discrete spaces, not continuous spaces.
  Instead, our proposed FSM synthesis algorithm operates in an unsupervised manner,
  leveraging low-level features from unprocessed, non-visual data, making it adaptable
  across various domains. The synthesized FSM models are expressive enough to be used
  in a model-based Reinforcement Learning scheme that leverages offline data to efficiently
  synthesize environment-specific world models. We demonstrate the advantages of SWMPO
  by benchmarking its environment modeling capabilities in simulated environments.
software: https://gitlab.com/da_doomer/swmpo
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hernandez-cano25a
month: 0
tex_title: Neurosymbolic World Models for Sequential Decision Making
firstpage: 23047
lastpage: 23062
page: 23047-23062
order: 23047
cycles: false
bibtex_author: Hernandez Cano, Leonardo and Perroni-Scharf, Maxine and Dhir, Neil
  and Ramamurthy, Arun and Solar-Lezama, Armando
author:
- given: Leonardo
  family: Hernandez Cano
- given: Maxine
  family: Perroni-Scharf
- given: Neil
  family: Dhir
- given: Arun
  family: Ramamurthy
- given: Armando
  family: Solar-Lezama
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/hernandez-cano25a/hernandez-cano25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
