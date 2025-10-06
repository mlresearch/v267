---
title: 'MERGE$^3$: Efficient Evolutionary Merging on Consumer-grade GPUs'
openreview: qFXDv0X4yc
abstract: Evolutionary model merging enables the creation of high-performing multi-task
  models but remains computationally prohibitive for consumer hardware. We introduce
  MERGE$^3$, an efficient framework that makes evolutionary merging of Large Language
  Models (LLMs) feasible on a single GPU by reducing fitness computation costs 50$\times$
  while retaining a large fraction of the original performance. MERGE$^3$ achieves
  this by <b>E</b>xtracting a reduced dataset for evaluation, <b>E</b>stimating model
  abilities using Item Response Theory (IRT), and <b>E</b>volving optimal merges via
  IRT-based performance estimators. Our method enables state-of-the-art multilingual
  and cross-lingual merging, transferring knowledge across languages with significantly
  lower computational overhead. We provide theoretical guarantees and an open-source
  library, democratizing high-quality model merging.
software: https://github.com/tommasomncttn/merge3
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mencattini25a
month: 0
tex_title: "{MERGE}$^3$: Efficient Evolutionary Merging on Consumer-grade {GPU}s"
firstpage: 43694
lastpage: 43715
page: 43694-43715
order: 43694
cycles: false
bibtex_author: Mencattini, Tommaso and Minut, Robert Adrian and Crisostomi, Donato
  and Santilli, Andrea and Rodol\`{a}, Emanuele
author:
- given: Tommaso
  family: Mencattini
- given: Robert Adrian
  family: Minut
- given: Donato
  family: Crisostomi
- given: Andrea
  family: Santilli
- given: Emanuele
  family: Rodolà
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/mencattini25a/mencattini25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
