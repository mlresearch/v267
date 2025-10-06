---
title: Random Feature Representation Boosting
openreview: iUDsgI8z1T
abstract: We introduce Random Feature Representation Boosting (RFRBoost), a novel
  method for constructing deep residual random feature neural networks (RFNNs) using
  boosting theory. RFRBoost uses random features at each layer to learn the functional
  gradient of the network representation, enhancing performance while preserving the
  convex optimization benefits of RFNNs. In the case of MSE loss, we obtain closed-form
  solutions to greedy layer-wise boosting with random features. For general loss functions,
  we show that fitting random feature residual blocks reduces to solving a quadratically
  constrained least squares problem. Through extensive numerical experiments on tabular
  datasets for both regression and classification, we show that RFRBoost significantly
  outperforms RFNNs and end-to-end trained MLP ResNets in the small- to medium-scale
  regime where RFNNs are typically applied. Moreover, RFRBoost offers substantial
  computational benefits, and theoretical guarantees stemming from boosting theory.
software: https://github.com/nikitazozoulenko/random-feature-representation-boosting
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: zozoulenko25a
month: 0
tex_title: Random Feature Representation Boosting
firstpage: 80900
lastpage: 80932
page: 80900-80932
order: 80900
cycles: false
bibtex_author: Zozoulenko, Nikita and Cass, Thomas and Gonon, Lukas
author:
- given: Nikita
  family: Zozoulenko
- given: Thomas
  family: Cass
- given: Lukas
  family: Gonon
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/zozoulenko25a/zozoulenko25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
