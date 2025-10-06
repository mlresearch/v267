---
title: Understanding Complexity in VideoQA via Visual Program Generation
openreview: 6GFPnVHEKB
abstract: We propose a data-driven approach to analyzing query complexity in Video
  Question Answering (VideoQA). Previous efforts in benchmark design have relied on
  human expertise to design challenging questions, yet we experimentally show that
  humans struggle to predict which questions are difficult for machine learning models.
  Our automatic approach leverages recent advances in code generation for visual question
  answering, using the complexity of generated code as a proxy for question difficulty.
  We demonstrate that this measure correlates significantly better with model performance
  than human estimates. To operationalize this insight, we propose an algorithm for
  estimating question complexity from code. It identifies fine-grained primitives
  that correlate with the hardest questions for any given set of models, making it
  easy to scale to new approaches in the future. Finally, to further illustrate the
  utility of our method, we extend it to automatically generate complex questions,
  constructing a new benchmark that is 1.9 times harder than the popular NExT-QA.
software: https://github.com/ceyzaguirre4/codeplexity
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: eyzaguirre25a
month: 0
tex_title: Understanding Complexity in {V}ideo{QA} via Visual Program Generation
firstpage: 15613
lastpage: 15636
page: 15613-15636
order: 15613
cycles: false
bibtex_author: Eyzaguirre, Cristobal and Vasiljevic, Igor and Dave, Achal and Wu,
  Jiajun and Ambrus, Rares Andrei and Kollar, Thomas and Niebles, Juan Carlos and
  Tokmakov, Pavel
author:
- given: Cristobal
  family: Eyzaguirre
- given: Igor
  family: Vasiljevic
- given: Achal
  family: Dave
- given: Jiajun
  family: Wu
- given: Rares Andrei
  family: Ambrus
- given: Thomas
  family: Kollar
- given: Juan Carlos
  family: Niebles
- given: Pavel
  family: Tokmakov
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/eyzaguirre25a/eyzaguirre25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
