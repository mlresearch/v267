---
title: Low-distortion and GPU-compatible Tree Embeddings in Hyperbolic Space
openreview: 47ghX0qpYW
abstract: Embedding tree-like data, from hierarchies to ontologies and taxonomies,
  forms a well-studied problem for representing knowledge across many domains. Hyperbolic
  geometry provides a natural solution for embedding trees, with vastly superior performance
  over Euclidean embeddings. Recent literature has shown that hyperbolic tree embeddings
  can even be placed on top of neural networks for hierarchical knowledge integration
  in deep learning settings. For all applications, a faithful embedding of trees is
  needed, with combinatorial constructions emerging as the most effective direction.
  This paper identifies and solves two key limitations of existing works. First, the
  combinatorial construction hinges on finding highly separated points on a hypersphere,
  a notoriously difficult problem. Current approaches achieve poor separation, degrading
  the quality of the corresponding hyperbolic embedding. We propose highly separated
  Delaunay tree embeddings (HS-DTE), which integrates angular separation in a generalized
  formulation of Delaunay embeddings, leading to lower embedding distortion. Second,
  low-distortion requires additional precision. The current approach for increasing
  precision is to use multiple precision arithmetic, which renders the embeddings
  useless on GPUs in deep learning settings. We reformulate the combinatorial construction
  using floating point expansion arithmetic, leading to superior embedding quality
  while retaining utility on accelerated hardware.
software: https://github.com/maxvanspengler/hyperbolic_tree_embeddings
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: van-spengler25a
month: 0
tex_title: Low-distortion and {GPU}-compatible Tree Embeddings in Hyperbolic Space
firstpage: 60792
lastpage: 60815
page: 60792-60815
order: 60792
cycles: false
bibtex_author: Van Spengler, Max and Mettes, Pascal
author:
- given: Max
  family: Van Spengler
- given: Pascal
  family: Mettes
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/van-spengler25a/van-spengler25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
