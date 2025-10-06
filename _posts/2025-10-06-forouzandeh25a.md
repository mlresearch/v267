---
title: 'SHARP-Distill: A 68$\times$ Faster Recommender System with Hypergraph Neural
  Networks and Language Models'
openreview: 3hYrORJndz
abstract: This paper proposes SHARP-Distill (<b>S</b>peedy <b>H</b>ypergraph <b>A</b>nd
  <b>R</b>eview-based <b>P</b>ersonalised <b>Distill</b>ation), a novel knowledge
  distillation approach based on the teacher-student framework that combines Hypergraph
  Neural Networks (HGNNs) with language models to enhance recommendation quality while
  significantly improving inference time. The teacher model leverages HGNNs to generate
  user and item embeddings from interaction data, capturing high-order and group relationships,
  and employing a pre-trained language model to extract rich semantic features from
  textual reviews. We utilize a contrastive learning mechanism to ensure structural
  consistency between various representations. The student includes a shallow and
  lightweight GCN called CompactGCN designed to inherit high-order relationships while
  reducing computational complexity. Extensive experiments on real-world datasets
  demonstrate that SHARP-Distill achieves up to 68$\times$ faster inference time compared
  to HGNN and 40$\times$ faster than LightGCN while maintaining competitive recommendation
  accuracy.
software: https://github.com/S-Forouzandeh/SHARP-Distill/tree/main
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: forouzandeh25a
month: 0
tex_title: "{SHARP}-Distill: A 68$\\times$ Faster Recommender System with Hypergraph
  Neural Networks and Language Models"
firstpage: 17452
lastpage: 17488
page: 17452-17488
order: 17452
cycles: false
bibtex_author: Forouzandeh, Saman and Moradi, Parham and Jalili, Mahdi
author:
- given: Saman
  family: Forouzandeh
- given: Parham
  family: Moradi
- given: Mahdi
  family: Jalili
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/forouzandeh25a/forouzandeh25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
