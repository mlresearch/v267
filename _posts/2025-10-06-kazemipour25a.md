---
title: Model-Based Exploration in Monitored Markov Decision Processes
openreview: GdsbEOwAE7
abstract: 'A tenet of reinforcement learning is that the agent always observes rewards.
  However, this is not true in many realistic settings, e.g., a human observer may
  not always be available to provide rewards, sensors may be limited or malfunctioning,
  or rewards may be inaccessible during deployment. Monitored Markov decision processes
  (Mon-MDPs) have recently been proposed to model such settings. However, existing
  Mon-MDP algorithms have several limitations: they do not fully exploit the problem
  structure, cannot leverage a known monitor, lack worst-case guarantees for "unsolvable"
  Mon-MDPs without specific initialization, and offer only asymptotic convergence
  proofs. This paper makes three contributions. First, we introduce a model-based
  algorithm for Mon-MDPs that addresses these shortcomings. The algorithm employs
  two instances of model-based interval estimation: one to ensure that observable
  rewards are reliably captured, and another to learn the minimax-optimal policy.
  Second, we empirically demonstrate the advantages. We show faster convergence than
  prior algorithms in more than four dozen benchmarks, and even more dramatic improvements
  when the monitoring process is known. Third, we present the first finite-sample
  bound on performance. We show convergence to a minimax-optimal policy even when
  some rewards are never observable.'
software: https://github.com/IRLL/Exploration-in-Mon-MDPs
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kazemipour25a
month: 0
tex_title: Model-Based Exploration in Monitored {M}arkov Decision Processes
firstpage: 29527
lastpage: 29556
page: 29527-29556
order: 29527
cycles: false
bibtex_author: Kazemipour, Alireza and Taylor, Matthew E. and Bowling, Michael
author:
- given: Alireza
  family: Kazemipour
- given: Matthew E.
  family: Taylor
- given: Michael
  family: Bowling
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/kazemipour25a/kazemipour25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
