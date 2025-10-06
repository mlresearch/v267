---
title: 'Comparing Few to Rank Many: Active Human Preference Learning Using Randomized
  Frank-Wolfe Method'
openreview: cUNfm13VUR
abstract: We study learning human preferences from limited comparison feedback, a
  core machine learning problem that is at the center of reinforcement learning from
  human feedback (RLHF). We formulate the problem as learning a Plackett-Luce (PL)
  model from a limited number of $K$-subset comparisons over a universe of $N$ items,
  where typically $K \ll N$. Our objective is to select the $K$-subsets such that
  all items can be ranked with minimal mistakes within the budget. We solve the problem
  using the D-optimal design, which minimizes the worst-case ranking loss under the
  estimated PL model. All known algorithms for this problem are computationally infeasible
  in our setting because we consider exponentially many subsets in $K$. To address
  this challenge, we propose a randomized Frank-Wolfe algorithm with memoization and
  sparse updates that has a low $O(N^2 + K^2)$ per-iteration complexity. We analyze
  it and demonstrate its empirical superiority on synthetic and open-source NLP datasets.
software: https://github.com/tkkiran/DopeWolfe
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: thekumparampil25a
month: 0
tex_title: 'Comparing Few to Rank Many: Active Human Preference Learning Using Randomized
  Frank-{W}olfe Method'
firstpage: 59355
lastpage: 59376
page: 59355-59376
order: 59355
cycles: false
bibtex_author: Thekumparampil, Kiran Koshy and Hiranandani, Gaurush and Kalantari,
  Kousha and Sabach, Shoham and Kveton, Branislav
author:
- given: Kiran Koshy
  family: Thekumparampil
- given: Gaurush
  family: Hiranandani
- given: Kousha
  family: Kalantari
- given: Shoham
  family: Sabach
- given: Branislav
  family: Kveton
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/thekumparampil25a/thekumparampil25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
