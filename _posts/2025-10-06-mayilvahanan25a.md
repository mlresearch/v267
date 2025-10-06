---
title: 'LLMs on the Line: Data Determines Loss-to-Loss Scaling Laws'
openreview: IVUjRWnU6c
abstract: Scaling laws guide the development of large language models (LLMs) by offering
  estimates for the optimal balance of model size, tokens, and compute. More recently,
  loss-to-loss scaling laws that relate losses across pretraining datasets and downstream
  tasks have emerged as a powerful tool for understanding and improving LLM performance
  and generalization. In this work, we investigate which factors most strongly influence
  loss-to-loss scaling. Our experiments reveal that the pretraining data determines
  the scaling trend. In contrast, model size, optimization hyperparameters, tokenizer
  and even significant architectural differences, such as between transformer-based
  models like Llama and state-space models like Mamba, generally have limited impact.
  Consequently, practitioners should carefully curate pretraining datasets for optimal
  downstream performance, while architectures and other settings can be freely optimized
  for training efficiency.
software: https://github.com/brendel-group/llm-line
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mayilvahanan25a
month: 0
tex_title: "{LLM}s on the Line: Data Determines Loss-to-Loss Scaling Laws"
firstpage: 43302
lastpage: 43330
page: 43302-43330
order: 43302
cycles: false
bibtex_author: Mayilvahanan, Prasanna and Wiedemer, Thadd\"{a}us and Mallick, Sayak
  and Bethge, Matthias and Brendel, Wieland
author:
- given: Prasanna
  family: Mayilvahanan
- given: Thaddäus
  family: Wiedemer
- given: Sayak
  family: Mallick
- given: Matthias
  family: Bethge
- given: Wieland
  family: Brendel
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/mayilvahanan25a/mayilvahanan25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
