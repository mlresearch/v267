---
title: 'AdaPTS: Adapting Univariate Foundation Models to Probabilistic Multivariate
  Time Series Forecasting'
openreview: yeICCRy3lE
abstract: Pre-trained foundation models (FMs) have shown exceptional performance in
  univariate time series forecasting tasks. However, several practical challenges
  persist, including managing intricate dependencies among features and quantifying
  uncertainty in predictions. This study aims to tackle these critical limitations
  by introducing <b>adapters</b>—feature-space transformations that facilitate the
  effective use of pre-trained univariate time series FMs for multivariate tasks.
  Adapters operate by projecting multivariate inputs into a suitable latent space
  and applying the FM independently to each dimension. Inspired by the literature
  on representation learning and partially stochastic Bayesian neural networks, we
  present a range of adapters and optimization/inference strategies. Experiments conducted
  on both synthetic and real-world datasets confirm the efficacy of adapters, demonstrating
  substantial enhancements in forecasting accuracy and uncertainty quantification
  compared to baseline methods. Our framework, <b>AdaPTS</b>, positions adapters as
  a modular, scalable, and effective solution for leveraging time series FMs in multivariate
  contexts, thereby promoting their wider adoption in real-world applications. We
  release the code at https://github.com/abenechehab/AdaPTS.
software: https://github.com/abenechehab/AdaPTS
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: benechehab25a
month: 0
tex_title: "{A}da{PTS}: Adapting Univariate Foundation Models to Probabilistic Multivariate
  Time Series Forecasting"
firstpage: 3731
lastpage: 3748
page: 3731-3748
order: 3731
cycles: false
bibtex_author: Benechehab, Abdelhakim and Feofanov, Vasilii and Paolo, Giuseppe and
  Thomas, Albert and Filippone, Maurizio and K\'{e}gl, Bal\'{a}zs
author:
- given: Abdelhakim
  family: Benechehab
- given: Vasilii
  family: Feofanov
- given: Giuseppe
  family: Paolo
- given: Albert
  family: Thomas
- given: Maurizio
  family: Filippone
- given: Balázs
  family: Kégl
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/benechehab25a/benechehab25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
