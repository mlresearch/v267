---
title: Conditioning Diffusions Using Malliavin Calculus
openreview: 0A4JSAU3FD
abstract: In generative modelling and stochastic optimal control, a central computational
  task is to modify a reference diffusion process to maximise a given terminal-time
  reward. Most existing methods require this reward to be differentiable, using gradients
  to steer the diffusion towards favourable outcomes. However, in many practical settings,
  like diffusion bridges, the reward is singular, taking an infinite value if the
  target is hit and zero otherwise. We introduce a novel framework, based on Malliavin
  calculus and centred around a generalisation of the Tweedie score formula to nonlinear
  stochastic differential equations, that enables the development of methods robust
  to such singularities. This allows our approach to handle a broad range of applications,
  like diffusion bridges, or adding conditional controls to an already trained diffusion
  model. We demonstrate that our approach offers stable and reliable training, outperforming
  existing techniques. As a byproduct, we also introduce a novel score matching objective.
  Our loss functions are formulated such that they could readily be extended to manifold-valued
  and infinite dimensional diffusions.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: pidstrigach25a
month: 0
tex_title: Conditioning Diffusions Using Malliavin Calculus
firstpage: 49292
lastpage: 49315
page: 49292-49315
order: 49292
cycles: false
bibtex_author: Pidstrigach, Jakiw and Baker, Elizabeth Louise and Domingo-Enrich,
  Carles and Deligiannidis, George and N\"{u}sken, Nikolas
author:
- given: Jakiw
  family: Pidstrigach
- given: Elizabeth Louise
  family: Baker
- given: Carles
  family: Domingo-Enrich
- given: George
  family: Deligiannidis
- given: Nikolas
  family: Nüsken
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/pidstrigach25a/pidstrigach25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
