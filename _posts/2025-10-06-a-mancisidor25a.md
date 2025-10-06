---
title: Aggregation of Dependent Expert Distributions in Multimodal Variational Autoencoders
openreview: jYmGi1175R
abstract: Multimodal learning with variational autoencoders (VAEs) requires estimating
  joint distributions to evaluate the evidence lower bound (ELBO). Current methods,
  the product and mixture of experts, aggregate single-modality distributions assuming
  independence for simplicity, which is an overoptimistic assumption. This research
  introduces a novel methodology for aggregating single-modality distributions by
  exploiting the principle of <em>consensus of dependent experts</em> (CoDE), which
  circumvents the aforementioned assumption. Utilizing the CoDE method, we propose
  a novel ELBO that approximates the joint likelihood of the multimodal data by learning
  the contribution of each subset of modalities. The resulting CoDE-VAE model demonstrates
  better performance in terms of balancing the trade-off between generative coherence
  and generative quality, as well as generating more precise log-likelihood estimations.
  CoDE-VAE further minimizes the generative quality gap as the number of modalities
  increases. In certain cases, it reaches a generative quality similar to that of
  unimodal VAEs, which is a desirable property that is lacking in most current methods.
  Finally, the classification accuracy achieved by CoDE-VAE is comparable to that
  of state-of-the-art multimodal VAE models.
software: https://github.com/rogelioamancisidor/codevae
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: a-mancisidor25a
month: 0
tex_title: Aggregation of Dependent Expert Distributions in Multimodal Variational
  Autoencoders
firstpage: 1
lastpage: 26
page: 1-26
order: 1
cycles: false
bibtex_author: A. Mancisidor, Rogelio and Jenssen, Robert and Yu, Shujian and Kampffmeyer,
  Michael
author:
- given: Rogelio
  family: A. Mancisidor
- given: Robert
  family: Jenssen
- given: Shujian
  family: Yu
- given: Michael
  family: Kampffmeyer
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/a-mancisidor25a/a-mancisidor25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
