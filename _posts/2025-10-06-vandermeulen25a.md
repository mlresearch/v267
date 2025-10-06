---
title: Dimension-Independent Rates for Structured Neural Density Estimation
openreview: o7mxIi8jRv
abstract: We show that deep neural networks can achieve dimension-independent rates
  of convergence for learning structured densities typical of image, audio, video,
  and text data. For example, in images, where each pixel becomes independent of the
  rest of the image when conditioned on pixels at most $t$ steps away, a simple $L^2$-minimizing
  neural network can attain a rate of $n^{-1/((t+1)^2+4)}$, where $t$ is independent
  of the ambient dimension $d$, i.e. the total number of pixels. We further provide
  empirical evidence that, in real-world applications, $t$ is often a small constant,
  thus effectively circumventing the curse of dimensionality. Moreover, for sequential
  data (e.g., audio or text) exhibiting a similar local dependence structure, our
  analysis shows a rate of $n^{-1/(t+5)}$, offering further evidence of dimension
  independence in practical scenarios.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: vandermeulen25a
month: 0
tex_title: Dimension-Independent Rates for Structured Neural Density Estimation
firstpage: 60857
lastpage: 60879
page: 60857-60879
order: 60857
cycles: false
bibtex_author: Vandermeulen, Robert A. and Tai, Wai Ming and Aragam, Bryon
author:
- given: Robert A.
  family: Vandermeulen
- given: Wai Ming
  family: Tai
- given: Bryon
  family: Aragam
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/vandermeulen25a/vandermeulen25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
