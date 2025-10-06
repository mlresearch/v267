---
title: Global curvature for second-order optimization of neural networks
openreview: f21sRSRb1E
abstract: 'Second-order optimization methods, which leverage the local curvature of
  the loss function, have the potential to dramatically accelerate the training of
  machine learning models. However, these methods are often hindered by the computational
  burden of constructing and inverting large curvature matrices with $\mathcal{O}(p^2)$
  elements, where $p$ is the number of parameters. In this work, we present a theory
  that predicts the <em>exact</em> structure of the global curvature by leveraging
  the intrinsic symmetries of neural networks, such as invariance under parameter
  permutations. For Multi-Layer Perceptrons (MLPs), our approach reveals that the
  global curvature can be expressed in terms of $\mathcal{O}(d^2 + L^2)$ independent
  factors, where $d$ is the number of input/output dimensions and $L$ is the number
  of layers, significantly reducing the computational burden compared to the $\mathcal{O}(p^2)$
  elements of the full matrix. These factors can be estimated efficiently, enabling
  precise curvature computations. To evaluate the practical implications of our framework,
  we apply second-order optimization to synthetic data, achieving markedly faster
  convergence compared to traditional optimization methods. Our findings pave the
  way for a better understanding of the loss landscape of neural networks, and for
  designing more efficient training methodologies in deep learning. Code: https://github.com/mtkresearch/symo_notebooks'
software: https://github.com/mtkresearch/symo_notebooks
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bernacchia25a
month: 0
tex_title: Global curvature for second-order optimization of neural networks
firstpage: 3843
lastpage: 3876
page: 3843-3876
order: 3843
cycles: false
bibtex_author: Bernacchia, Alberto
author:
- given: Alberto
  family: Bernacchia
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/bernacchia25a/bernacchia25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
