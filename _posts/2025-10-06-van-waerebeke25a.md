---
title: When to Forget? Complexity Trade-offs in Machine Unlearning
openreview: uEUIeIrRPv
abstract: 'Machine Unlearning (MU) aims at removing the influence of specific data
  points from a trained model, striving to achieve this at a fraction of the cost
  of full model retraining. In this paper, we analyze the efficiency of unlearning
  methods and establish the first upper and lower bounds on minimax computation times
  for this problem, characterizing the performance of the most efficient algorithm
  against the most difficult objective function. Specifically, for strongly convex
  objective functions and under the assumption that the forget data is inaccessible
  to the unlearning method, we provide a phase diagram for the <em>unlearning complexity
  ratio</em>—a novel metric that compares the computational cost of the best unlearning
  method to full model retraining. The phase diagram reveals three distinct regimes:
  one where unlearning at a reduced cost is infeasible, another where unlearning is
  trivial because adding noise suffices, and a third where unlearning achieves significant
  computational advantages over retraining. These findings highlight the critical
  role of factors such as data dimensionality, the number of samples to forget, and
  privacy constraints in determining the practical feasibility of unlearning.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: van-waerebeke25a
month: 0
tex_title: When to Forget? {C}omplexity Trade-offs in Machine Unlearning
firstpage: 60816
lastpage: 60832
page: 60816-60832
order: 60816
cycles: false
bibtex_author: Van Waerebeke, Martin and Lorenzi, Marco and Neglia, Giovanni and Scaman,
  Kevin
author:
- given: Martin
  family: Van Waerebeke
- given: Marco
  family: Lorenzi
- given: Giovanni
  family: Neglia
- given: Kevin
  family: Scaman
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/van-waerebeke25a/van-waerebeke25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
