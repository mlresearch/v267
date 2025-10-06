---
title: 'Universal Sparse Autoencoders: Interpretable Cross-Model Concept Alignment'
openreview: UoaxRN88oR
abstract: We present Universal Sparse Autoencoders (USAEs), a framework for uncovering
  and aligning interpretable concepts spanning multiple pretrained deep neural networks.
  Unlike existing concept-based interpretability methods, which focus on a single
  model, USAEs jointly learn a universal concept space that can reconstruct and interpret
  the internal activations of multiple models at once. Our core insight is to train
  a single, overcomplete sparse autoencoder (SAE) that ingests activations from any
  model and decodes them to approximate the activations of any other model under consideration.
  By optimizing a shared objective, the learned dictionary captures common factors
  of variation—concepts—across different tasks, architectures, and datasets. We show
  that USAEs discover semantically coherent and important universal concepts across
  vision models; ranging from low-level features (e.g., colors and textures) to higher-level
  structures (e.g., parts and objects). Overall, USAEs provide a powerful new method
  for interpretable cross-model analysis and offers novel applications—such as coordinated
  activation maximization—that open avenues for deeper insights in multi-model AI
  systems.
software: https://github.com/YorkUCVIL/UniversalSAE
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: thasarathan25a
month: 0
tex_title: 'Universal Sparse Autoencoders: Interpretable Cross-Model Concept Alignment'
firstpage: 59304
lastpage: 59325
page: 59304-59325
order: 59304
cycles: false
bibtex_author: Thasarathan, Harrish and Forsyth, Julian and Fel, Thomas and Kowal,
  Matthew and Derpanis, Konstantinos G.
author:
- given: Harrish
  family: Thasarathan
- given: Julian
  family: Forsyth
- given: Thomas
  family: Fel
- given: Matthew
  family: Kowal
- given: Konstantinos G.
  family: Derpanis
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/thasarathan25a/thasarathan25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
