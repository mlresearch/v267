---
title: 'Compression via Pre-trained Transformers: A Study on Byte-Level Multimodal
  Data'
openreview: c5R0lKLIr3
abstract: Foundation models are strong data compressors, but when accounting for their
  parameter size, their compression ratios are inferior to standard compression algorithms.
  Naively reducing the parameter count does not necessarily help as it deteriorates
  predictions and, accordingly, compression. We conduct a large-scale empirical study
  to find a sweet spot where pre-trained vanilla transformers can achieve competitive
  compression ratios. To this end, we train models on 165GB of raw byte sequences
  of either text, image, or audio data (and all possible combinations of the three)
  and then compress 1GB of out-of-distribution (OOD) data from each modality. We find
  that relatively small models (millions of parameters) can outperform standard general-purpose
  compression algorithms (gzip, LZMA2) and even domain-specific compressors (PNG,
  JPEG-XL, FLAC) — even when accounting for parameter size. We achieve, e.g., the
  lowest compression ratio of 0.49 on OOD audio data (vs. 0.54 for FLAC). We conduct
  extensive ablations and hyperparameter sweeps to study the impact of model- and
  dataset scale, and we investigate the effect of unimodal versus multimodal training.
  We find that even small models can be trained to perform well on multiple modalities,
  but unlike large-scale foundation models, transfer to unseen modalities is generally
  weak.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: heurtel-depeiges25a
month: 0
tex_title: 'Compression via Pre-trained Transformers: A Study on Byte-Level Multimodal
  Data'
firstpage: 23120
lastpage: 23135
page: 23120-23135
order: 23120
cycles: false
bibtex_author: Heurtel-Depeiges, David and Ruoss, Anian and Veness, Joel and Genewein,
  Tim
author:
- given: David
  family: Heurtel-Depeiges
- given: Anian
  family: Ruoss
- given: Joel
  family: Veness
- given: Tim
  family: Genewein
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/heurtel-depeiges25a/heurtel-depeiges25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
