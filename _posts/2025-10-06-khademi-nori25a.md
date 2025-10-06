---
title: Autoencoder-Based Hybrid Replay for Class-Incremental Learning
openreview: fi6p2dBDNd
abstract: In class-incremental learning (CIL), effective incremental learning strategies
  are essential to mitigate task confusion and catastrophic forgetting, especially
  as the number of tasks $t$ increases. Current exemplar replay strategies impose
  $\mathcal{O}(t)$ memory/compute complexities. We propose an autoencoder-based hybrid
  replay (AHR) strategy that leverages our new hybrid autoencoder (HAE) to function
  as a compressor to alleviate the requirement for large memory, achieving $\mathcal{O}(0.1
  t)$ at the worst case with the computing complexity of $\mathcal{O}(t)$ while accomplishing
  state-of-the-art performance. The decoder later recovers the exemplar data stored
  in the latent space, rather than in raw format. Additionally, HAE is designed for
  both discriminative and generative modeling, enabling classification and replay
  capabilities, respectively. HAE adopts the charged particle system energy minimization
  equations and repulsive force algorithm for the incremental embedding and distribution
  of new class centroids in its latent space. Our results demonstrate that AHR consistently
  outperforms recent baselines across multiple benchmarks while operating with the
  same memory/compute budgets. The source code is included in the supplementary material
  and will be open-sourced upon publication.
software: https://github.com/miladkhademinori/autoencoder-hybrid-replay-cil
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: khademi-nori25a
month: 0
tex_title: Autoencoder-Based Hybrid Replay for Class-Incremental Learning
firstpage: 29753
lastpage: 29767
page: 29753-29767
order: 29753
cycles: false
bibtex_author: Khademi Nori, Milad and Kim, Il Min and Wang, Guanghui
author:
- given: Milad
  family: Khademi Nori
- given: Il Min
  family: Kim
- given: Guanghui
  family: Wang
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/khademi-nori25a/khademi-nori25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
