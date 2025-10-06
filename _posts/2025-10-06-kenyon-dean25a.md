---
title: 'ViTally Consistent: Scaling Biological Representation Learning for Cell Microscopy'
openreview: rS3ufabhQr
abstract: 'Deriving insights from experimentally generated datasets requires methods
  that can account for random and systematic measurement errors and remove them in
  order to accurately represent the underlying effects of the conditions being tested.
  Here we present a framework for pretraining on large-scale microscopy datasets that
  includes three steps: (1) curating a set of diverse and self-consistent training
  samples, (2) scaling training of an appropriate foundation model architecture on
  this dataset, (3) evaluating intermediate layers of the trained model to identify
  the best representation for downstream tasks. Using this strategy, we present the
  largest foundation model for cell microscopy data to our knowledge, a new 1.9 billion-parameter
  ViT-G/8 MAE trained on over 8 billion microscopy image crops. Compared to a previous
  published ViT-L/8 MAE, our new model achieves a 60% improvement in linear separability
  of genetic perturbations and obtains the best overall performance on whole-genome
  relationship recall, batch correction replicate consistency, and compound-gene activity
  prediction benchmarks.'
software: https://huggingface.co/recursionpharma/OpenPhenom
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kenyon-dean25a
month: 0
tex_title: "{V}i{T}ally Consistent: Scaling Biological Representation Learning for
  Cell Microscopy"
firstpage: 29735
lastpage: 29752
page: 29735-29752
order: 29735
cycles: false
bibtex_author: Kenyon-Dean, Kian and Wang, Zitong Jerry and Urbanik, John and Donhauser,
  Konstantin and Hartford, Jason and Saberian, Saber and Sahin, Nil and Bendidi, Ihab
  and Celik, Safiye and Vera, Juan Sebasti\'{a}n Rodr\'{\i}guez and Fay, Marta and
  Haque, Imran S and Kraus, Oren
author:
- given: Kian
  family: Kenyon-Dean
- given: Zitong Jerry
  family: Wang
- given: John
  family: Urbanik
- given: Konstantin
  family: Donhauser
- given: Jason
  family: Hartford
- given: Saber
  family: Saberian
- given: Nil
  family: Sahin
- given: Ihab
  family: Bendidi
- given: Safiye
  family: Celik
- given: Juan Sebastián Rodrı́guez
  family: Vera
- given: Marta
  family: Fay
- given: Imran S
  family: Haque
- given: Oren
  family: Kraus
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/kenyon-dean25a/kenyon-dean25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
