---
title: 'TimePoint: Accelerated Time Series Alignment via Self-Supervised Keypoint
  and Descriptor Learning'
openreview: bUGdGaNFhi
abstract: Fast and scalable alignment of time series is a fundamental challenge in
  many domains. The standard solution, Dynamic Time Warping (DTW), struggles with
  poor scalability and sensitivity to noise. We introduce TimePoint, a self-supervised
  method that dramatically accelerates DTW-based alignment while typically improving
  alignment accuracy by learning keypoints and descriptors from synthetic data. Inspired
  by 2D keypoint detection but carefully adapted to the unique challenges of 1D signals,
  TimePoint leverages efficient 1D diffeomorphisms, which effectively model nonlinear
  time warping, to generate realistic training data. This adaptation, along with fully
  convolutional and wavelet convolutional architectures, enables the extraction of
  informative keypoints and descriptors. Applying DTW to these sparse representations
  yields major speedups and typically higher alignment accuracy than standard DTW
  applied to the full signals. Despite being trained solely on synthetic data, TimePoint
  generalizes well to real-world time series. Extensive experiments demonstrate that
  TimePoint consistently achieves faster and more accurate alignments than standard
  DTW, making it a scalable solution for time-series analysis. Our code is available
  at https://github.com/ BGU-CS-VIL/TimePoint.
software: https://github.com/BGU-CS-VIL/TimePoint
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: shapira-weber25a
month: 0
tex_title: "{T}ime{P}oint: Accelerated Time Series Alignment via Self-Supervised Keypoint
  and Descriptor Learning"
firstpage: 54275
lastpage: 54299
page: 54275-54299
order: 54275
cycles: false
bibtex_author: Shapira Weber, Ron and Benishay, Shahar and Lavrinenko, Andrey and
  Finder, Shahaf E. and Freifeld, Oren
author:
- given: Ron
  family: Shapira Weber
- given: Shahar
  family: Benishay
- given: Andrey
  family: Lavrinenko
- given: Shahaf E.
  family: Finder
- given: Oren
  family: Freifeld
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/shapira-weber25a/shapira-weber25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
