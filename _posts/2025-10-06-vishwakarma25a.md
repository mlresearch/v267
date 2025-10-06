---
title: Rethinking Confidence Scores and Thresholds in Pseudolabeling-based SSL
openreview: w4c5bLkhsz
abstract: Modern semi-supervised learning (SSL) methods rely on pseudolabeling and
  consistency regularization. Pseudolabeling is typically performed by comparing the
  model’s confidence scores and a predefined threshold. While several heuristics have
  been proposed to improve threshold selection, the underlying issues of overconfidence
  and miscalibration in confidence scores remain largely unaddressed, leading to inaccurate
  pseudolabels, degraded test accuracy, and prolonged training. We take a first-principles
  approach to learn confidence scores and thresholds with an explicit knob for error.
  This flexible framework addresses the fundamental question of optimal scores and
  threshold selection in pseudolabeling. Moreover, it gives practitioners a principled
  way to control the quality and quantity of pseudolabels. Such control is vital in
  SSL, where balancing pseudolabel quality and quantity directly affects model performance
  and training efficiency. Our experiments show that, by integrating this framework
  with modern SSL methods, we achieve significant improvements in accuracy and training
  efficiency. In addition, we provide novel insights on the trade-offs between the
  choices of the error parameter and the end model’s performance.
software: https://github.com/harit7/PabLO-SSL
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: vishwakarma25a
month: 0
tex_title: Rethinking Confidence Scores and Thresholds in Pseudolabeling-based {SSL}
firstpage: 61582
lastpage: 61600
page: 61582-61600
order: 61582
cycles: false
bibtex_author: Vishwakarma, Harit and Chen, Yi and Namburi Gnvv, Satya Sai Srinath
  and Tay, Sui Jiet and Vinayak, Ramya Korlakai and Sala, Frederic
author:
- given: Harit
  family: Vishwakarma
- given: Yi
  family: Chen
- given: Satya Sai Srinath
  family: Namburi Gnvv
- given: Sui Jiet
  family: Tay
- given: Ramya Korlakai
  family: Vinayak
- given: Frederic
  family: Sala
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/vishwakarma25a/vishwakarma25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
