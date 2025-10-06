---
title: 'Prune ’n Predict: Optimizing LLM Decision-making with Conformal Prediction'
openreview: 5g6LPR0Dlx
abstract: Large language models (LLMs) are empowering decision-making in several applications,
  including tool or API usage and answering multiple-choice questions (MCQs). However,
  incorrect outputs pose significant risks in high-stakes domains like healthcare
  and finance. To quantify LLM uncertainty and thereby mitigate these risks, recent
  works employ conformal prediction (CP), a model- and distribution-agnostic framework
  that uses LLM outputs to generate a <em>prediction set</em> containing the true
  answer with high probability. Leveraging CP, we propose <em>conformal revision of
  questions</em> (CROQ), which revises the question by narrowing down the available
  choices to those in the prediction set and asking the LLM the revised question.
  We expect LLMs to be more accurate on revised questions with fewer choices. Furthermore,
  we expect CROQ to be effective when the prediction sets from CP are small. Commonly
  used logit scores often lead to large sets, diminishing CROQ’s effectiveness. To
  overcome this, we propose CP-OPT, an optimization framework to learn scores that
  minimize set sizes while maintaining coverage. Our extensive experiments on MMLU,
  ToolAlpaca, and TruthfulQA datasets with multiple LLMs show that CROQ improves accuracy
  over the standard inference, with more pronounced gains when paired with CP-OPT.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: vishwakarma25b
month: 0
tex_title: 'Prune ’n Predict: Optimizing {LLM} Decision-making with Conformal Prediction'
firstpage: 61601
lastpage: 61634
page: 61601-61634
order: 61601
cycles: false
bibtex_author: Vishwakarma, Harit and Mishler, Alan and Cook, Thomas and Dalmasso,
  Niccolo and Raman, Natraj and Ganesh, Sumitra
author:
- given: Harit
  family: Vishwakarma
- given: Alan
  family: Mishler
- given: Thomas
  family: Cook
- given: Niccolo
  family: Dalmasso
- given: Natraj
  family: Raman
- given: Sumitra
  family: Ganesh
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/vishwakarma25b/vishwakarma25b.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
