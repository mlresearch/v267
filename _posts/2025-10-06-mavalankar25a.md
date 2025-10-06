---
title: 'AuPair: Golden Example Pairs for Code Repair'
openreview: GmqZ3WvkeV
abstract: Scaling up inference-time compute has proven to be a valuable strategy in
  improving the performance of Large Language Models (LLMs) without fine-tuning. An
  important task that can benefit from additional inference-time compute is self-repair;
  given an initial flawed response or guess, the LLM corrects its own mistake and
  produces an improved response or fix. We leverage the in-context learning ability
  of LLMs to perform self-repair in the coding domain. The key contribution of our
  paper is an approach that synthesises and selects an ordered set of golden example
  pairs, or AuPairs, of these initial guesses and subsequent fixes for the corresponding
  problems. Each such AuPair is provided as a single in-context example at inference
  time to generate a repaired solution. For an inference-time compute budget of $N$
  LLM calls per problem, $N$ AuPairs are used to generate $N$ repaired solutions,
  out of which the highest-scoring solution is the final answer. The underlying intuition
  is that if the LLM is given a different example of fixing an incorrect guess each
  time, it can subsequently generate a diverse set of repaired solutions. Our algorithm
  selects these AuPairs in a manner that maximises complementarity and usefulness.
  We demonstrate the results of our algorithm on 5 LLMs across 7 competitive programming
  datasets for the code repair task. Our algorithm yields a significant boost in performance
  compared to best-of-$N$ and self-repair, and also exhibits strong generalisation
  across datasets and models. Moreover, our approach shows stronger scaling with inference-time
  compute budget compared to baselines.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mavalankar25a
month: 0
tex_title: "{A}u{P}air: Golden Example Pairs for Code Repair"
firstpage: 43276
lastpage: 43301
page: 43276-43301
order: 43276
cycles: false
bibtex_author: Mavalankar, Aditi and Mansoor, Hassan and Marinho, Zita and Samsikova,
  Mariia and Schaul, Tom
author:
- given: Aditi
  family: Mavalankar
- given: Hassan
  family: Mansoor
- given: Zita
  family: Marinho
- given: Mariia
  family: Samsikova
- given: Tom
  family: Schaul
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/mavalankar25a/mavalankar25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
