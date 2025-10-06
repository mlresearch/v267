---
title: 'Learning Minimum-Size BDDs: Towards Efficient Exact Algorithms'
openreview: aPMB4uwBmK
abstract: Binary decision diagrams (BDDs) are widely applied tools to compactly represent
  labeled data as directed acyclic graphs; for efficiency and interpretability reasons
  small BDDs are preferred. Given labeled data, minimizing BDDs is NP-complete and
  thus recent research focused on the influence of parameters such as the solution
  size $s$ on the complexity [Ordyniak et al., AAAI 2024]. Our main positive result
  is an algorithm that is efficient if in particular $s$, the domain size $D$, and
  the Hamming distance between any two data points is small, improving on previous
  running-time bounds. This algorithm is inspired by the witness-tree paradigm that
  was recently successful for computing decision trees [Komusiewicz et al., ICML 2023],
  whose extension to BDDs was open. We extend our algorithmic results to the case
  where we allow a small number of misclassified data points and complement them with
  lower bounds that show that the running times are tight from multiple points of
  view. We show that our main algorithm holds practical promise by providing a proof-of-concept
  implementation.
software: https://doi.org/10.5281/zenodo.15489411
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: komusiewicz25a
month: 0
tex_title: 'Learning Minimum-Size {BDD}s: Towards Efficient Exact Algorithms'
firstpage: 31322
lastpage: 31341
page: 31322-31341
order: 31322
cycles: false
bibtex_author: Komusiewicz, Christian and Schidler, Andre and Sommer, Frank and Sorge,
  Manuel and Staus, Luca Pascal
author:
- given: Christian
  family: Komusiewicz
- given: Andre
  family: Schidler
- given: Frank
  family: Sommer
- given: Manuel
  family: Sorge
- given: Luca Pascal
  family: Staus
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/komusiewicz25a/komusiewicz25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
