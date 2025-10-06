---
title: Uncertainty Estimation for Heterophilic Graphs Through the Lens of Information
  Theory
openreview: GDvO6viRCF
abstract: While uncertainty estimation for graphs recently gained traction, most methods
  rely on homophily and deteriorate in heterophilic settings. We address this by analyzing
  message passing neural networks from an information-theoretic perspective and developing
  a suitable analog to data processing inequality to quantify information throughout
  the model’s layers. In contrast to non-graph domains, information about the node-level
  prediction target can <em>increase</em> with model depth if a node’s features are
  semantically different from its neighbors. Therefore, on heterophilic graphs, the
  latent embeddings of an MPNN each provide different information about the data distribution
  - different from homophilic settings. This reveals that considering all node representations
  simultaneously is a key design principle for epistemic uncertainty estimation on
  graphs beyond homophily. We empirically confirm this with a simple post-hoc density
  estimator on the joint node embedding space that provides state-of-the-art uncertainty
  on heterophilic graphs. At the same time, it matches prior work on homophilic graphs
  without explicitly exploiting homophily through post-processing.
software: https://www.cs.cit.tum.de/daml/heterophilic-uncertainty/
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: fuchsgruber25a
month: 0
tex_title: Uncertainty Estimation for Heterophilic Graphs Through the Lens of Information
  Theory
firstpage: 17928
lastpage: 17959
page: 17928-17959
order: 17928
cycles: false
bibtex_author: Fuchsgruber, Dominik and Wollschl\"{a}ger, Tom and Bordne, Johannes
  and G\"{u}nnemann, Stephan
author:
- given: Dominik
  family: Fuchsgruber
- given: Tom
  family: Wollschläger
- given: Johannes
  family: Bordne
- given: Stephan
  family: Günnemann
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/fuchsgruber25a/fuchsgruber25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
