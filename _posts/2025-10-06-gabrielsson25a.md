---
title: 'Compress then Serve: Serving Thousands of LoRA Adapters with Little Overhead'
openreview: 3XMA8RDJu2
abstract: Fine-tuning large language models (LLMs) with low-rank adaptations (LoRAs)
  has become common practice, often yielding numerous copies of the same LLM differing
  only in their LoRA updates. This paradigm presents challenges for systems that serve
  real-time responses to queries that each involve a different LoRA. Prior works optimize
  the design of such systems but still require continuous loading and offloading of
  LoRAs, as it is infeasible to store thousands of LoRAs in GPU memory. To mitigate
  this issue, we investigate the efficacy of compression when serving LoRAs. We propose
  a method for the joint compression of LoRAs into a shared basis paired with LoRA-specific
  scaling matrices. We extend our algorithm to learn clusters of LoRAs that are amenable
  to joint compression, allowing it to scale gracefully to large LoRA collections.
  Our experiments with up to 1000 LoRAs demonstrate that compressed LoRAs preserve
  performance while offering major throughput gains in realistic serving scenarios
  with over a thousand LoRAs, maintaining 80% of the throughput of serving a single
  LoRA.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gabrielsson25a
month: 0
tex_title: 'Compress then Serve: Serving Thousands of {L}o{RA} Adapters with Little
  Overhead'
firstpage: 18062
lastpage: 18095
page: 18062-18095
order: 18062
cycles: false
bibtex_author: Gabrielsson, Rickard Br\"{u}el and Zhu, Jiacheng and Bhardwaj, Onkar
  and Choshen, Leshem and Greenewald, Kristjan and Yurochkin, Mikhail and Solomon,
  Justin
author:
- given: Rickard Brüel
  family: Gabrielsson
- given: Jiacheng
  family: Zhu
- given: Onkar
  family: Bhardwaj
- given: Leshem
  family: Choshen
- given: Kristjan
  family: Greenewald
- given: Mikhail
  family: Yurochkin
- given: Justin
  family: Solomon
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/gabrielsson25a/gabrielsson25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
