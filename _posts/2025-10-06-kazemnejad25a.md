---
title: 'VinePPO: Refining Credit Assignment in RL Training of LLMs'
openreview: Myx2kJFzAn
abstract: 'Large language models (LLMs) are increasingly applied to complex reasoning
  tasks that require executing several complex steps before receiving any reward.
  Properly assigning credit to these steps is essential for enhancing model performance.
  Proximal Policy Optimization (PPO), a common reinforcement learning (RL) algorithm
  used for LLM finetuning, employs value networks to tackle credit assignment. However,
  recent approaches achieve strong results without it, raising questions about the
  efficacy of value networks in practice. In this work, we systematically evaluate
  the efficacy of value networks and reveal their significant shortcomings in reasoning-heavy
  LLM tasks, showing that they often produce poor estimate of expected return and
  barely outperform a random baseline when comparing alternative steps. This motivates
  our key question: Can improved credit assignment enhance RL training for LLMs? To
  address this, we propose VinePPO, a straightforward approach that leverages the
  flexibility of language environments to compute unbiased Monte Carlo-based estimates.
  Our method consistently outperforms PPO and other baselines across MATH and GSM8K
  datasets in less wall-clock time (up to 3.0x). Crucially, it achieves higher test
  accuracy for a given training accuracy, capturing more generalization signal per
  sample. These results emphasize the importance of accurate credit assignment in
  RL training of LLM.'
software: https://github.com/McGill-NLP/VinePPO
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kazemnejad25a
month: 0
tex_title: "{V}ine{PPO}: Refining Credit Assignment in {RL} Training of {LLM}s"
firstpage: 29557
lastpage: 29590
page: 29557-29590
order: 29557
cycles: false
bibtex_author: Kazemnejad, Amirhossein and Aghajohari, Milad and Portelance, Eva and
  Sordoni, Alessandro and Reddy, Siva and Courville, Aaron and Le Roux, Nicolas
author:
- given: Amirhossein
  family: Kazemnejad
- given: Milad
  family: Aghajohari
- given: Eva
  family: Portelance
- given: Alessandro
  family: Sordoni
- given: Siva
  family: Reddy
- given: Aaron
  family: Courville
- given: Nicolas
  family: Le Roux
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/kazemnejad25a/kazemnejad25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
