---
title: 'Canonical Rank Adaptation: An Efficient Fine-Tuning Strategy for Vision Transformers'
openreview: vexHifrbJg
abstract: Modern methods for fine-tuning a Vision Transformer (ViT) like Low-Rank
  Adaptation (LoRA) and its variants demonstrate impressive performance. However,
  these methods ignore the high-dimensional nature of Multi-Head Attention (MHA) weight
  tensors. To address this limitation, we propose Canonical Rank Adaptation (CaRA).
  CaRA leverages tensor mathematics, first by tensorising the transformer into two
  different tensors; one for projection layers in MHA and the other for feed-forward
  layers. Second, the tensorised formulation is fine-tuned using the low-rank adaptation
  in Canonical-Polyadic Decomposition (CPD) form. Employing CaRA efficiently minimizes
  the number of trainable parameters. Experimentally, CaRA outperforms existing Parameter-Efficient
  Fine-Tuning (PEFT) methods in visual classification benchmarks such as Visual Task
  Adaptation Benchmark (VTAB)-1k and Fine-Grained Visual Categorization (FGVC).
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: veeramacheneni25a
month: 0
tex_title: 'Canonical Rank Adaptation: An Efficient Fine-Tuning Strategy for Vision
  Transformers'
firstpage: 61108
lastpage: 61125
page: 61108-61125
order: 61108
cycles: false
bibtex_author: Veeramacheneni, Lokesh and Wolter, Moritz and Kuehne, Hilde and Gall,
  Juergen
author:
- given: Lokesh
  family: Veeramacheneni
- given: Moritz
  family: Wolter
- given: Hilde
  family: Kuehne
- given: Juergen
  family: Gall
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/veeramacheneni25a/veeramacheneni25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
