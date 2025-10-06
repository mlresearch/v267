---
title: Provably Efficient RL for Linear MDPs under Instantaneous Safety Constraints
  in Non-Convex Feature Spaces
openreview: sElAqKsJrQ
abstract: In Reinforcement Learning (RL), tasks with instantaneous hard constraints
  present significant challenges, particularly when the decision space is non-convex
  or non-star-convex. This issue is especially relevant in domains like autonomous
  vehicles and robotics, where constraints such as collision avoidance often take
  a non-convex form. In this paper, we establish a regret bound of $\tilde{\mathcal{O}}((1
  + \tfrac{1}{\tau}) \sqrt{\log(\frac{1}{\tau}) d^3 H^4 K})$, applicable to both star-convex
  and non-star-convex cases, where $d$ is the feature dimension, $H$ the episode length,
  $K$ the number of episodes, and $\tau$ the safety threshold. Moreover, the violation
  of safety constraints is zero with high probability throughout the learning process.
  A key technical challenge in these settings is bounding the covering number of the
  value-function class, which is essential for achieving value-aware uniform concentration
  in model-free function approximation. For the star-convex setting, we develop a
  novel technique called <em>Objective–Constraint Decomposition</em> (OCD) to properly
  bound the covering number. This result also resolves an error in a previous work
  on constrained RL. In non-star-convex scenarios, where the covering number can become
  infinitely large, we propose a two-phase algorithm, Non-Convex Safe Least Squares
  Value Iteration (NCS-LSVI), which first reduces uncertainty about the safe set by
  playing a known safe policy. After that, it carefully balances exploration and exploitation
  to achieve the regret bound. Finally, numerical simulations on an autonomous driving
  scenario demonstrate the effectiveness of NCS-LSVI.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: roknilamouki25a
month: 0
tex_title: Provably Efficient {RL} for Linear {MDP}s under Instantaneous Safety Constraints
  in Non-Convex Feature Spaces
firstpage: 51957
lastpage: 51995
page: 51957-51995
order: 51957
cycles: false
bibtex_author: Roknilamouki, Amirhossein and Ghosh, Arnob and Shi, Ming and Nourzad,
  Fatemeh and Ekici, Eylem and Shroff, Ness
author:
- given: Amirhossein
  family: Roknilamouki
- given: Arnob
  family: Ghosh
- given: Ming
  family: Shi
- given: Fatemeh
  family: Nourzad
- given: Eylem
  family: Ekici
- given: Ness
  family: Shroff
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/roknilamouki25a/roknilamouki25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
