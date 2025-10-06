---
title: 'LEAPS: A discrete neural sampler via locally equivariant networks'
openreview: Hq2RniQAET
abstract: We propose <em>LEAPS</em>, an algorithm to sample from discrete distributions
  known up to normalization by learning a rate matrix of a continuous-time Markov
  chain (CTMC). LEAPS can be seen as a continuous-time formulation of annealed importance
  sampling and sequential Monte Carlo methods, extended so that the variance of the
  importance weights is offset by the inclusion of the CTMC. To derive these importance
  weights, we introduce a set of Radon-Nikodym derivatives of CTMCs over their path
  measures. Because the computation of these weights is intractable with standard
  neural network parameterizations of rate matrices, we devise a new compact representation
  for rate matrices via what we call <em>locally equivariant</em> functions. To parameterize
  them, we introduce a family of locally equivariant multilayer perceptrons, attention
  layers, and convolutional networks, and provide an approach to make deep networks
  that preserve the local equivariance. This property allows us to propose a scalable
  training algorithm for the rate matrix such that the variance of the importance
  weights associated to the CTMC are minimal. We demonstrate the efficacy of LEAPS
  on problems in statistical physics. We provide code in https://github.com/malbergo/leaps/.
software: https://github.com/malbergo/leaps/
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: holderrieth25a
month: 0
tex_title: "{LEAPS}: A discrete neural sampler via locally equivariant networks"
firstpage: 23397
lastpage: 23416
page: 23397-23416
order: 23397
cycles: false
bibtex_author: Holderrieth, Peter and Albergo, Michael Samuel and Jaakkola, Tommi
author:
- given: Peter
  family: Holderrieth
- given: Michael Samuel
  family: Albergo
- given: Tommi
  family: Jaakkola
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/holderrieth25a/holderrieth25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
