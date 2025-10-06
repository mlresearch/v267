---
title: Diffusion on Language Model Encodings for Protein Sequence Generation
openreview: xB9eROwBCB
abstract: Protein <em>sequence</em> design has seen significant advances through discrete
  diffusion and autoregressive approaches, yet the potential of continuous diffusion
  remains underexplored. Here, we present <em>DiMA</em>, a latent diffusion framework
  that operates on protein language model representations. Through systematic exploration
  of architectural choices and diffusion components, we develop a robust methodology
  that generalizes across multiple protein encoders ranging from 8M to 3B parameters.
  We demonstrate that our framework achieves consistently high performance across
  sequence-only (ESM-2, ESMc), dual-decodable (CHEAP), and multimodal (SaProt) representations
  using the same architecture and training approach. We conduct extensive evaluation
  of existing methods alongside <em>DiMA</em> using multiple metrics across two protein
  modalities, covering quality, diversity, novelty, and distribution matching of generated
  proteins. <em>DiMA</em> consistently produces novel, high-quality and diverse protein
  sequences and achieves strong results compared to baselines such as autoregressive,
  discrete diffusion and flow matching language models. The model demonstrates versatile
  functionality, supporting conditional generation tasks including protein family-generation,
  motif scaffolding and infilling, and fold-specific sequence design, despite being
  trained solely on sequence data. This work provides a universal continuous diffusion
  framework for protein sequence generation, offering both architectural insights
  and practical applicability across various protein design scenarios. Code is released
  at GitHub.
software: https://github.com/MeshchaninovViacheslav/DiMA
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: meshchaninov25a
month: 0
tex_title: Diffusion on Language Model Encodings for Protein Sequence Generation
firstpage: 43837
lastpage: 43878
page: 43837-43878
order: 43837
cycles: false
bibtex_author: Meshchaninov, Viacheslav and Strashnov, Pavel and Shevtsov, Andrey
  and Nikolaev, Fedor and Ivanisenko, Nikita and Kardymon, Olga and Vetrov, Dmitry
author:
- given: Viacheslav
  family: Meshchaninov
- given: Pavel
  family: Strashnov
- given: Andrey
  family: Shevtsov
- given: Fedor
  family: Nikolaev
- given: Nikita
  family: Ivanisenko
- given: Olga
  family: Kardymon
- given: Dmitry
  family: Vetrov
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/meshchaninov25a/meshchaninov25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
