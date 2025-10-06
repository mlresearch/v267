---
title: Online Linear Classification with Massart Noise
openreview: VFM6BcxCd2
abstract: We study the task of online learning in the presence of Massart noise. Specifically,
  instead of assuming that the online adversary chooses an arbitrary sequence of labels,
  we assume that the context $\boldsymbol{x}$ is selected adversarially but the label
  $y$ presented to the learner disagrees with the ground-truth label of $\boldsymbol{x}$
  with unknown probability <em>at most</em> $\eta$. We focus on the fundamental class
  of $\gamma$-margin linear classifiers and present the first computationally efficient
  algorithm that achieves mistake bound $\eta T + o(T)$. We point out that the mistake
  bound achieved by our algorithm is qualitatively tight for computationally efficient
  algorithms; this follows from the fact that, even in the offline setting, achieving
  0-1 error better than $\eta$ requires super-polynomial time under standard complexity
  assumptions. We extend our online learning model to a $k$-arm contextual bandit
  setting where the rewards—instead of satisfying commonly used realizability assumptions—are
  consistent, in expectation, with some linear ranking function with weight vector
  $\boldsymbol{w}^\ast$. Given a list of contexts $\boldsymbol{x}_1,\ldots \boldsymbol{x}_k$,
  if $\boldsymbol{w}^*\cdot \boldsymbol{x}_i > \boldsymbol{w}^* \cdot \boldsymbol{x}_j$,
  the expected reward of action $i$ must be larger than that of $j$ by at least $\Delta$.
  We use our Massart online learner to design an efficient bandit algorithm that obtains
  expected reward at least $(1-1/k) \Delta T - o(T)$ bigger than choosing a random
  action at every round.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: diakonikolas25e
month: 0
tex_title: Online Linear Classification with Massart Noise
firstpage: 13679
lastpage: 13692
page: 13679-13692
order: 13679
cycles: false
bibtex_author: Diakonikolas, Ilias and Kontonis, Vasilis and Tzamos, Christos and
  Zarifis, Nikos
author:
- given: Ilias
  family: Diakonikolas
- given: Vasilis
  family: Kontonis
- given: Christos
  family: Tzamos
- given: Nikos
  family: Zarifis
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/diakonikolas25e/diakonikolas25e.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
