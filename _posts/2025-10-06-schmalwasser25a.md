---
title: 'FastCAV: Efficient Computation of Concept Activation Vectors for Explaining
  Deep Neural Networks'
openreview: kRmfzTfIGe
abstract: Concepts such as objects, patterns, and shapes are how humans understand
  the world. Building on this intuition, concept-based explainability methods aim
  to study representations learned by deep neural networks in relation to human-understandable
  concepts. Here, Concept Activation Vectors (CAVs) are an important tool and can
  identify whether a model learned a concept or not. However, the computational cost
  and time requirements of existing CAV computation pose a significant challenge,
  particularly in large-scale, high-dimensional architectures. To address this limitation,
  we introduce FastCAV, a novel approach that accelerates the extraction of CAVs by
  up to 63.6$\times$ (on average 46.4$\times$). We provide a theoretical foundation
  for our approach and give concrete assumptions under which it is equivalent to established
  SVM-based methods. Our empirical results demonstrate that CAVs calculated with FastCAV
  maintain similar performance while being more efficient and stable. In downstream
  applications, i.e., concept-based explanation methods, we show that FastCAV can
  act as a replacement leading to equivalent insights. Hence, our approach enables
  previously infeasible investigations of deep models, which we demonstrate by tracking
  the evolution of concepts during model training.
software: https://fastcav.github.io/
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: schmalwasser25a
month: 0
tex_title: "{F}ast{CAV}: Efficient Computation of Concept Activation Vectors for Explaining
  Deep Neural Networks"
firstpage: 53316
lastpage: 53342
page: 53316-53342
order: 53316
cycles: false
bibtex_author: Schmalwasser, Laines and Penzel, Niklas and Denzler, Joachim and Niebling,
  Julia
author:
- given: Laines
  family: Schmalwasser
- given: Niklas
  family: Penzel
- given: Joachim
  family: Denzler
- given: Julia
  family: Niebling
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/schmalwasser25a/schmalwasser25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
