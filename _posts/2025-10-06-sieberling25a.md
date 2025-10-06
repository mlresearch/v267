---
title: 'EvoPress: Accurate Dynamic Model Compression via Evolutionary Search'
openreview: l7QzcZpjc5
abstract: 'The high computational costs of large language models (LLMs) have led to
  a flurry of research on LLM compression, via methods such as quantization, sparsification,
  or structured pruning. A new frontier in this area is given by dynamic, non-uniform
  compression methods, which adjust the compression levels (e.g., sparsity) per-block
  or even per-layer in order to minimize accuracy loss, while guaranteeing a global
  compression threshold. Yet, current methods rely on estimating the "importance"
  of a given layer, implicitly assuming that layers contribute independently to the
  overall compression error. We begin from the motivating observation that this independence
  assumption does not generally hold for LLM compression: pruning a model further
  may even significantly recover performance. To address this, we propose EvoPress,
  a novel evolutionary framework for dynamic LLM compression. By formulating dynamic
  compression as a general optimization problem, EvoPress identifies optimal compression
  profiles in a highly efficient manner, and generalizes across diverse models and
  compression techniques. Via EvoPress, we achieve state-of-the-art performance for
  dynamic compression of Llama, Mistral, and Phi models, setting new benchmarks for
  structural pruning (block/layer dropping), unstructured sparsity, and quantization
  with dynamic bitwidths.'
software: https://github.com/IST-DASLab/EvoPress
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sieberling25a
month: 0
tex_title: "{E}vo{P}ress: Accurate Dynamic Model Compression via Evolutionary Search"
firstpage: 55556
lastpage: 55590
page: 55556-55590
order: 55556
cycles: false
bibtex_author: Sieberling, Oliver and Kuznedelev, Denis and Kurtic, Eldar and Alistarh,
  Dan
author:
- given: Oliver
  family: Sieberling
- given: Denis
  family: Kuznedelev
- given: Eldar
  family: Kurtic
- given: Dan
  family: Alistarh
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/sieberling25a/sieberling25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
