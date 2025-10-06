---
title: Constrained Belief Updates Explain Geometric Structures in Transformer Representations
openreview: f6Hl60FBFU
abstract: What computational structures emerge in transformers trained on next-token
  prediction? In this work, we provide evidence that transformers implement constrained
  Bayesian belief updating—a parallelized version of partial Bayesian inference shaped
  by architectural constraints. We integrate the model-agnostic theory of optimal
  prediction with mechanistic interpretability to analyze transformers trained on
  a tractable family of hidden Markov models that generate rich geometric patterns
  in neural activations. Our primary analysis focuses on single-layer transformers,
  revealing how the first attention layer implements these constrained updates, with
  extensions to multi-layer architectures demonstrating how subsequent layers refine
  these representations. We find that attention carries out an algorithm with a natural
  interpretation in the probability simplex, and create representations with distinctive
  geometric structure. We show how both the algorithmic behavior and the underlying
  geometry of these representations can be theoretically predicted in detail—including
  the attention pattern, OV-vectors, and embedding vectors—by modifying the equations
  for optimal future token predictions to account for the architectural constraints
  of attention. Our approach provides a principled lens on how architectural constraints
  shape the implementation of optimal prediction, revealing why transformers develop
  specific intermediate geometric structures.
software: https://github.com/adamimos/epsilon-transformers/blob/main/examples/intermediate_representations.ipynb
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: piotrowski25a
month: 0
tex_title: Constrained Belief Updates Explain Geometric Structures in Transformer
  Representations
firstpage: 49399
lastpage: 49419
page: 49399-49419
order: 49399
cycles: false
bibtex_author: Piotrowski, Mateusz and Riechers, Paul M. and Filan, Daniel and Shai,
  Adam
author:
- given: Mateusz
  family: Piotrowski
- given: Paul M.
  family: Riechers
- given: Daniel
  family: Filan
- given: Adam
  family: Shai
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/piotrowski25a/piotrowski25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
