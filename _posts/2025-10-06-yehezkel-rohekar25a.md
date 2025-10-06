---
title: 'A Causal World Model Underlying Next Token Prediction: Exploring GPT in a
  Controlled Environment'
openreview: qA3xHJzF6B
abstract: Are generative pre-trained transformer (GPT) models, trained only to predict
  the next token, implicitly learning a world model from which sequences are generated
  one token at a time? We address this question by deriving a causal interpretation
  of the attention mechanism in GPT and presenting a causal world model that arises
  from this interpretation. Furthermore, we propose that GPT models, at inference
  time, can be utilized for zero-shot causal structure learning for input sequences,
  and introduce a corresponding confidence score. Empirical tests were conducted in
  controlled environments using the setups of the Othello and Chess strategy games.
  A GPT, pre-trained on real-world games played with the intention of winning, was
  tested on out-of-distribution synthetic data consisting of sequences of random legal
  moves. We find that the GPT model is likely to generate legal next moves for out-of-distribution
  sequences for which a causal structure is encoded in the attention mechanism with
  high confidence. In cases where it generates illegal moves, it also fails to capture
  a causal structure.
software: https://github.com/IntelLabs/causality-lab
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: yehezkel-rohekar25a
month: 0
tex_title: 'A Causal World Model Underlying Next Token Prediction: Exploring {GPT}
  in a Controlled Environment'
firstpage: 72196
lastpage: 72209
page: 72196-72209
order: 72196
cycles: false
bibtex_author: Yehezkel Rohekar, Raanan and Gurwicz, Yaniv and Yu, Sungduk and Aflalo,
  Estelle and Lal, Vasudev
author:
- given: Raanan
  family: Yehezkel Rohekar
- given: Yaniv
  family: Gurwicz
- given: Sungduk
  family: Yu
- given: Estelle
  family: Aflalo
- given: Vasudev
  family: Lal
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/yehezkel-rohekar25a/yehezkel-rohekar25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
