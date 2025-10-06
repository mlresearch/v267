---
title: 'Not All Wrong is Bad: Using Adversarial Examples for Unlearning'
openreview: BkrIQPREkn
abstract: 'Machine unlearning, where users can request the deletion of a forget dataset,
  is becoming increasingly important because of numerous privacy regulations. Initial
  works on "exact” unlearning (e.g., retraining) incur large computational overheads.
  However, while computationally inexpensive, "approximate” methods have fallen short
  of reaching the effectiveness of exact unlearning: models produced fail to obtain
  comparable accuracy and prediction confidence on both the forget and test (i.e.,
  unseen) dataset. Exploiting this observation, we propose a new unlearning method,
  Adversarial Machine UNlearning (AMUN), that outperforms prior state-of-the-art (SOTA)
  methods for image classification. AMUN lowers the confidence of the model on the
  forget samples by fine-tuning the model on their corresponding adversarial examples.
  Adversarial examples naturally belong to the distribution imposed by the model on
  the input space; fine-tuning the model on the adversarial examples closest to the
  corresponding forget samples (a) localizes the changes to the decision boundary
  of the model around each forget sample and (b) avoids drastic changes to the global
  behavior of the model, thereby preserving the model’s accuracy on test samples.
  Using AMUN for unlearning a random 10% of CIFAR-10 samples, we observe that even
  SOTA membership inference attacks cannot do better than random guessing.'
software: https://github.com/Ali-E/AMUN
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ebrahimpour-boroojeny25a
month: 0
tex_title: 'Not All Wrong is Bad: Using Adversarial Examples for Unlearning'
firstpage: 14950
lastpage: 14971
page: 14950-14971
order: 14950
cycles: false
bibtex_author: Ebrahimpour-Boroojeny, Ali and Sundaram, Hari and Chandrasekaran, Varun
author:
- given: Ali
  family: Ebrahimpour-Boroojeny
- given: Hari
  family: Sundaram
- given: Varun
  family: Chandrasekaran
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/ebrahimpour-boroojeny25a/ebrahimpour-boroojeny25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
