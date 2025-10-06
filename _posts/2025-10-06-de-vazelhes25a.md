---
title: 'Optimization over Sparse Support-Preserving Sets: Two-Step Projection with
  Global Optimality Guarantees'
openreview: B0hE61qHMp
abstract: In sparse optimization, enforcing hard constraints using the $\ell_0$ pseudo-norm
  offers advantages like controlled sparsity compared to convex relaxations. However,
  many real-world applications demand not only sparsity constraints but also some
  extra constraints. While prior algorithms have been developed to address this complex
  scenario with mixed combinatorial and convex constraints, they typically require
  the closed form projection onto the mixed constraints which might not exist, and/or
  only provide local guarantees of convergence which is different from the global
  guarantees commonly sought in sparse optimization. To fill this gap, in this paper,
  we study the problem of sparse optimization with extra <em>support-preserving</em>
  constraints commonly encountered in the literature. We present a new variant of
  iterative hard-thresholding algorithm equipped with a two-step consecutive projection
  operator customized for these mixed constraints, serving as a simple alternative
  to the Euclidean projection onto the mixed constraint. By introducing a novel trade-off
  between sparsity relaxation and sub-optimality, we provide global guarantees in
  objective value for the output of our algorithm, in the deterministic, stochastic,
  and zeroth-order settings, under the conventional restricted strong-convexity/smoothness
  assumptions. As a fundamental contribution in proof techniques, we develop a novel
  extension of the classic three-point lemma to the considered two-step non-convex
  projection operator, which allows us to analyze the convergence in objective value
  in an elegant way that has not been possible with existing techniques. In the zeroth-order
  case, such technique also improves upon the state-of-the-art result from de Vazelhes
  et. al. (2022), even in the case without additional constraints, by allowing us
  to remove a non-vanishing system error present in their work.
software: https://github.com/wdevazelhes/2SP_icml2025
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: de-vazelhes25a
month: 0
tex_title: 'Optimization over Sparse Support-Preserving Sets: Two-Step Projection
  with Global Optimality Guarantees'
firstpage: 12840
lastpage: 12900
page: 12840-12900
order: 12840
cycles: false
bibtex_author: De Vazelhes, William and Yuan, Xiaotong and Gu, Bin
author:
- given: William
  family: De Vazelhes
- given: Xiaotong
  family: Yuan
- given: Bin
  family: Gu
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/de-vazelhes25a/de-vazelhes25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
