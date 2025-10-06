---
title: Improving Continual Learning Performance and Efficiency with Auxiliary Classifiers
openreview: sq5eL4jfsn
abstract: Continual learning is crucial for applying machine learning in challenging,
  dynamic, and often resource-constrained environments. However, catastrophic forgetting
  — overwriting previously learned knowledge when new information is acquired — remains
  a major challenge. In this work, we examine the intermediate representations in
  neural network layers during continual learning and find that such representations
  are less prone to forgetting, highlighting their potential to accelerate computation.
  Motivated by these findings, we propose to use auxiliary classifiers (ACs) to enhance
  performance and demonstrate that integrating ACs into various continual learning
  methods consistently improves accuracy across diverse evaluation settings, yielding
  an average 10% relative gain. We also leverage the ACs to reduce the average cost
  of the inference by 10-60% without compromising accuracy, enabling the model to
  return the predictions before computing all the layers. Our approach provides a
  scalable and efficient solution for continual learning.
software: https://github.com/fszatkowski/cl-auxiliary-classifiers
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: szatkowski25a
month: 0
tex_title: Improving Continual Learning Performance and Efficiency with Auxiliary
  Classifiers
firstpage: 58106
lastpage: 58141
page: 58106-58141
order: 58106
cycles: false
bibtex_author: Szatkowski, Filip and Zheng, Yaoyue and Yang, Fei and Trzcinski, Tomasz
  and Twardowski, Bart{\l}omiej and Van De Weijer, Joost
author:
- given: Filip
  family: Szatkowski
- given: Yaoyue
  family: Zheng
- given: Fei
  family: Yang
- given: Tomasz
  family: Trzcinski
- given: Bartłomiej
  family: Twardowski
- given: Joost
  family: Van De Weijer
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/szatkowski25a/szatkowski25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
