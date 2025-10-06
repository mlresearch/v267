---
title: 'NoLiMa: Long-Context Evaluation Beyond Literal Matching'
openreview: 0OshX1hiSa
abstract: Recent large language models (LLMs) support long contexts ranging from 128K
  to 1M tokens. A popular method for evaluating these capabilities is the needle-in-a-haystack
  (NIAH) test, which involves retrieving a "needle" (relevant information) from a
  "haystack" (long irrelevant context). Extensions of this approach include increasing
  distractors, fact chaining, and in-context reasoning. However, in these benchmarks,
  models can exploit existing literal matches between the needle and haystack to simplify
  the task. To address this, we introduce NoLiMa, a benchmark extending NIAH with
  a carefully designed needle set, where questions and needles have minimal lexical
  overlap, requiring models to infer latent associations to locate the needle within
  the haystack. We evaluate 13 popular LLMs that claim to support contexts of at least
  128K tokens. While they perform well in short contexts ($<$1K), performance degrades
  significantly as context length increases. At 32K, for instance, 11 models drop
  below 50% of their strong short-length baselines. Even GPT-4o, one of the top-performing
  exceptions, experiences a reduction from an almost-perfect baseline of 99.3% to
  69.7%. Our analysis suggests these declines stem from the increased difficulty the
  attention mechanism faces in longer contexts when literal matches are absent, making
  it harder to retrieve relevant information. Even models enhanced with reasoning
  capabilities or CoT prompting struggle to maintain performance in long contexts.
  We publicly release the dataset and evaluation code at https://github.com/adobe-research/NoLiMa.
software: https://github.com/adobe-research/NoLiMa
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: modarressi25a
month: 0
tex_title: "{N}o{L}i{M}a: Long-Context Evaluation Beyond Literal Matching"
firstpage: 44554
lastpage: 44570
page: 44554-44570
order: 44554
cycles: false
bibtex_author: Modarressi, Ali and Deilamsalehy, Hanieh and Dernoncourt, Franck and
  Bui, Trung and Rossi, Ryan A. and Yoon, Seunghyun and Schuetze, Hinrich
author:
- given: Ali
  family: Modarressi
- given: Hanieh
  family: Deilamsalehy
- given: Franck
  family: Dernoncourt
- given: Trung
  family: Bui
- given: Ryan A.
  family: Rossi
- given: Seunghyun
  family: Yoon
- given: Hinrich
  family: Schuetze
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/modarressi25a/modarressi25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
