---
title: 'Optimal Decision Tree Pruning Revisited: Algorithms and Complexity'
openreview: iUsHLRTp3t
abstract: We present a comprehensive classical and parameterized complexity analysis
  of decision tree pruning operations, extending recent research on the complexity
  of learning small decision trees. Thereby, we offer new insights into the computational
  challenges of decision tree simplification, a crucial aspect of developing interpretable
  and efficient machine learning models. We focus on fundamental pruning operations
  of subtree replacement and raising, which are used in heuristics. Surprisingly,
  while optimal pruning can be performed in polynomial time for subtree replacement,
  the problem is NP-complete for subtree raising. Therefore, we identify parameters
  and combinations thereof that lead to fixed-parameter tractability or hardness,
  establishing a precise borderline between these complexity classes. For example,
  while subtree raising is hard for small domain size $D$ or number $d$ of features,
  it can be solved in $D^{2d} \cdot |I|^{O(1)}$ time, where $|I|$ is the input size.
  We complement our theoretical findings with preliminary experimental results, demonstrating
  the practical implications of our analysis.
software: https://doi.org/10.5281/zenodo.15534096
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: harviainen25a
month: 0
tex_title: 'Optimal Decision Tree Pruning Revisited: Algorithms and Complexity'
firstpage: 22177
lastpage: 22203
page: 22177-22203
order: 22177
cycles: false
bibtex_author: Harviainen, Juha and Sommer, Frank and Sorge, Manuel and Szeider, Stefan
author:
- given: Juha
  family: Harviainen
- given: Frank
  family: Sommer
- given: Manuel
  family: Sorge
- given: Stefan
  family: Szeider
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/harviainen25a/harviainen25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
