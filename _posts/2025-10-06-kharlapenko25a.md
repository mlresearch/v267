---
title: Scaling Sparse Feature Circuits For Studying In-Context Learning
openreview: Mp8Og8Rpop
abstract: Sparse autoencoders (SAEs) are a popular tool for interpreting large language
  model activations, but their utility in addressing open questions in interpretability
  remains unclear. In this work, we demonstrate their effectiveness by using SAEs
  to deepen our understanding of the mechanism behind in-context learning (ICL). We
  identify abstract SAE features that (i) encode the model’s knowledge of which task
  to execute and (ii) whose latent vectors causally induce the task zero-shot. This
  aligns with prior work showing that ICL is mediated by task vectors. We further
  demonstrate that these task vectors are well approximated by a sparse sum of SAE
  latents, including these task-execution features. To explore the ICL mechanism,
  we scale the sparse feature circuits methodology of Marks et al. (2024) to the Gemma
  1 2B model for the more complex task of ICL. Through circuit finding, we discover
  task-detecting features with corresponding SAE latents that activate earlier in
  the prompt, that detect when tasks have been performed. They are causally linked
  with task-execution features through the attention and MLP sublayers.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kharlapenko25a
month: 0
tex_title: Scaling Sparse Feature Circuits For Studying In-Context Learning
firstpage: 29819
lastpage: 29851
page: 29819-29851
order: 29819
cycles: false
bibtex_author: Kharlapenko, Dmitrii and Shabalin, Stepan and Conmy, Arthur and Nanda,
  Neel
author:
- given: Dmitrii
  family: Kharlapenko
- given: Stepan
  family: Shabalin
- given: Arthur
  family: Conmy
- given: Neel
  family: Nanda
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/kharlapenko25a/kharlapenko25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
