---
title: Learning multivariate Gaussians with imperfect advice
openreview: 0OVCcpLNGI
abstract: We revisit the problem of distribution learning within the framework of
  learning-augmented algorithms. In this setting, we explore the scenario where a
  probability distribution is provided as potentially inaccurate advice on the true,
  unknown distribution. Our objective is to develop learning algorithms whose sample
  complexity decreases as the quality of the advice improves, thereby surpassing standard
  learning lower bounds when the advice is sufficiently accurate. Specifically, we
  demonstrate that this outcome is achievable for the problem of learning a multivariate
  Gaussian distribution $N(\mu, \Sigma)$ in the PAC learning setting. Classically,
  in the advice-free setting, $\widetilde{\Theta}(d^2/\varepsilon^2)$ samples are
  sufficient and worst case necessary to learn $d$-dimensional Gaussians up to TV
  distance $\varepsilon$ with constant probability. When we are additionally given
  a parameter $\widetilde{\Sigma}$ as advice, we show that $\widetilde{\mathcal{O}}(d^{2-\beta}/\varepsilon^2)$
  samples suffices whenever $|| \widetilde{\Sigma}^{-1/2} \Sigma \widetilde{\Sigma}^{-1/2}
  - I_d ||_1 \leq \varepsilon d^{1-\beta}$ (where $||\cdot||_1$ denotes the entrywise
  $\ell_1$ norm) for any $\beta > 0$, yielding a polynomial improvement over the advice-free
  setting.
software: https://github.com/philips-george/gaussian-learning-with-advice
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bhattacharyya25a
month: 0
tex_title: Learning multivariate {G}aussians with imperfect advice
firstpage: 4210
lastpage: 4252
page: 4210-4252
order: 4210
cycles: false
bibtex_author: Bhattacharyya, Arnab and Choo, Davin and George John, Philips and Gouleakis,
  Themis
author:
- given: Arnab
  family: Bhattacharyya
- given: Davin
  family: Choo
- given: Philips
  family: George John
- given: Themis
  family: Gouleakis
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/bhattacharyya25a/bhattacharyya25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
