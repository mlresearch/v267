---
title: 'Positional Attention: Expressivity and Learnability of Algorithmic Computation'
openreview: 0IJQD8zRXT
abstract: 'There is a growing interest in the ability of neural networks to execute
  algorithmic tasks (e.g., arithmetic, summary statistics, and sorting). The goal
  of this work is to better understand the role of attention in Transformers for algorithmic
  execution. Its importance for algorithmic execution has been studied theoretically
  and empirically using parallel computational models. Notably, many parallel algorithms
  communicate between processors solely using positional information. Inspired by
  this observation, we investigate how Transformers can execute algorithms using positional
  attention, where attention weights depend exclusively on positional encodings. We
  prove that Transformers with positional attention (positional Transformers) maintain
  the same expressivity of parallel computational models, incurring a logarithmic
  depth cost relative to the input length. We analyze their in-distribution learnability
  and explore how parameter norms in positional attention affect sample complexity.
  Our results show that positional Transformers introduce a learning trade-off: while
  they exhibit better theoretical dependence on parameter norms, certain tasks may
  require more layers, which can, in turn, increase sample complexity. Finally, we
  empirically explore the out-of-distribution performance of positional Transformers
  and find that they perform well in tasks where their underlying algorithmic solution
  relies on positional information.'
software: https://github.com/opallab/positional_attention
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: back-de-luca25a
month: 0
tex_title: 'Positional Attention: Expressivity and Learnability of Algorithmic Computation'
firstpage: 2335
lastpage: 2390
page: 2335-2390
order: 2335
cycles: false
bibtex_author: Back De Luca, Artur and Giapitzakis, George and Yang, Shenghao and
  Veli\v{c}kovi\'{c}, Petar and Fountoulakis, Kimon
author:
- given: Artur
  family: Back De Luca
- given: George
  family: Giapitzakis
- given: Shenghao
  family: Yang
- given: Petar
  family: Veličković
- given: Kimon
  family: Fountoulakis
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/back-de-luca25a/back-de-luca25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
