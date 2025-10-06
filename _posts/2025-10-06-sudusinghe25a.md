---
title: 'COGNATE: Acceleration of Sparse Tensor Programs on Emerging Hardware using
  Transfer Learning'
openreview: EV0itGFjmm
abstract: 'Sparse tensor programs are essential in deep learning and graph analytics,
  driving the need for optimized processing. To meet this demand, specialized hardware
  accelerators are being developed. Optimizing these programs for accelerators is
  challenging for two reasons: program performance is highly sensitive to variations
  in sparse inputs, and early-stage accelerators rely on expensive simulators. Therefore,
  ML-based cost models used for optimizing such programs on general-purpose hardware
  are often ineffective for early-stage accelerators, as they require large datasets
  for proper training. To this end, we introduce COGNATE, a novel framework that leverages
  inexpensive data samples from general-purpose hardware (e.g., CPUs) to train cost
  models, followed by few-shot fine-tuning on emerging hardware. COGNATE exploits
  the homogeneity of input features across hardware platforms while effectively mitigating
  heterogeneity, enabling cost model training with just 5% of the data samples needed
  by accelerator-specific models to achieve comparable performance. We conduct extensive
  experiments to demonstrate that COGNATE outperforms existing techniques, achieving
  average speedups of 1.47$\times$ (up to 5.46$\times$) for SpMM and 1.39$\times$
  (up to 4.22$\times$) for SDDMM.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sudusinghe25a
month: 0
tex_title: "{COGNATE}: Acceleration of Sparse Tensor Programs on Emerging Hardware
  using Transfer Learning"
firstpage: 57231
lastpage: 57248
page: 57231-57248
order: 57231
cycles: false
bibtex_author: Sudusinghe, Chamika and Gerogiannis, Gerasimos and Lenadora, Damitha
  and Block, Charles and Torrellas, Josep and Mendis, Charith
author:
- given: Chamika
  family: Sudusinghe
- given: Gerasimos
  family: Gerogiannis
- given: Damitha
  family: Lenadora
- given: Charles
  family: Block
- given: Josep
  family: Torrellas
- given: Charith
  family: Mendis
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/sudusinghe25a/sudusinghe25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
