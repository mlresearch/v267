---
title: 'Differential Privacy Under Class Imbalance: Methods and Empirical Insights'
openreview: SgIg3cZjuN
abstract: Imbalanced learning occurs in classification settings where the distribution
  of class-labels is highly skewed in the training data, such as when predicting rare
  diseases or in fraud detection. This class imbalance presents a significant algorithmic
  challenge, which can be further exacerbated when privacy-preserving techniques such
  as differential privacy are applied to protect sensitive training data. Our work
  formalizes these challenges and provides a number of algorithmic solutions. We consider
  DP variants of pre-processing methods that privately augment the original dataset
  to reduce the class imbalance, alongside DP variants of in-processing techniques,
  which adjust the learning algorithm to account for the imbalance. For each method,
  we either adapt an existing imbalanced learning technique to the private setting
  or demonstrate its incompatibility with differential privacy. Finally, we empirically
  evaluate these privacy-preserving imbalanced learning methods under various data
  and distributional settings. We find that private synthetic data methods perform
  well as a data pre-processing step, while class-weighted ERMs are an alternative
  in higher-dimensional settings where private synthetic data suffers from the curse
  of dimensionality.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: rosenblatt25b
month: 0
tex_title: 'Differential Privacy Under Class Imbalance: Methods and Empirical Insights'
firstpage: 52065
lastpage: 52109
page: 52065-52109
order: 52065
cycles: false
bibtex_author: Rosenblatt, Lucas and Lut, Yuliia and Turok, Ethan and Medina, Marco
  Avella and Cummings, Rachel
author:
- given: Lucas
  family: Rosenblatt
- given: Yuliia
  family: Lut
- given: Ethan
  family: Turok
- given: Marco Avella
  family: Medina
- given: Rachel
  family: Cummings
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/rosenblatt25b/rosenblatt25b.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
