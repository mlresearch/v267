---
title: 'Adjusting Model Size in Continual Gaussian Processes: How Big is Big Enough?'
openreview: 9vYGZX4OVN
abstract: Many machine learning models require setting a parameter that controls their
  size before training, e.g. number of neurons in DNNs, or inducing points in GPs.
  Increasing capacity typically improves performance until all the information from
  the dataset is captured. After this point, computational cost keeps increasing,
  without improved performance. This leads to the question "How big is big enough?"
  We investigate this problem for Gaussian processes (single-layer neural networks)
  in continual learning. Here, data becomes available incrementally, and the final
  dataset size will therefore not be known before training, preventing the use of
  heuristics for setting a fixed model size. We develop a method to automatically
  adjust model size while maintaining near-optimal performance. Our experimental procedure
  follows the constraint that any hyperparameters must be set without seeing dataset
  properties, and we show that our method performs well across diverse datasets without
  the need to adjust its hyperparameter, showing it requires less tuning than others.
software: https://github.com/guiomarpescador/vips
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: pescador-barrios25a
month: 0
tex_title: 'Adjusting Model Size in Continual {G}aussian Processes: How Big is Big
  Enough?'
firstpage: 48974
lastpage: 49000
page: 48974-49000
order: 48974
cycles: false
bibtex_author: Pescador-Barrios, Guiomar and Filippi, Sarah Lucie and Van Der Wilk,
  Mark
author:
- given: Guiomar
  family: Pescador-Barrios
- given: Sarah Lucie
  family: Filippi
- given: Mark
  family: Van Der Wilk
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/pescador-barrios25a/pescador-barrios25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
