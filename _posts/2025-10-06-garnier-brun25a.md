---
title: 'How Transformers Learn Structured Data: Insights From Hierarchical Filtering'
openreview: AVXApuBCvN
abstract: Understanding the learning process and the embedded computation in transformers
  is becoming a central goal for the development of interpretable AI. In the present
  study, we introduce a hierarchical filtering procedure for data models of sequences
  on trees, allowing us to hand-tune the range of positional correlations in the data.
  Leveraging this controlled setting, we provide evidence that vanilla encoder-only
  transformers can approximate the exact inference algorithm when trained on root
  classification and masked language modeling tasks, and study <em>how</em> this computation
  is discovered and implemented. We find that correlations at larger distances, corresponding
  to increasing layers of the hierarchy, are sequentially included by the network
  during training. By comparing attention maps from models trained with varying degrees
  of filtering and by probing the different encoder levels, we find clear evidence
  of a reconstruction of correlations on successive length scales corresponding to
  the various levels of the hierarchy, which we relate to a plausible implementation
  of the exact inference algorithm within the same architecture.
software: https://github.com/emanuele-moscato/tree-language
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: garnier-brun25a
month: 0
tex_title: 'How Transformers Learn Structured Data: Insights From Hierarchical Filtering'
firstpage: 18831
lastpage: 18847
page: 18831-18847
order: 18831
cycles: false
bibtex_author: Garnier-Brun, Jerome and Mezard, Marc and Moscato, Emanuele and Saglietti,
  Luca
author:
- given: Jerome
  family: Garnier-Brun
- given: Marc
  family: Mezard
- given: Emanuele
  family: Moscato
- given: Luca
  family: Saglietti
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/garnier-brun25a/garnier-brun25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
