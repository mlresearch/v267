---
title: 'From Jack of All Trades to Master of One: Specializing LLM-based Autoraters
  to a Test Set'
openreview: Y0Kxvmjkmh
abstract: As LLMs continue to become more powerful and versatile, human evaluation
  has become intractable at scale and reliance on automatic metrics has become the
  norm. Recently, it has been shown that LLMs are themselves state-of-the-art evaluators
  for many tasks. These <em>Autoraters</em> are typically designed so that they generalize
  to new systems <em>and</em> test sets. In practice, however, evaluation is performed
  on a small set of fixed, canonical test sets, which are carefully curated to measure
  the capabilities of interest and are not changed frequently. In this work, we design
  a method which specializes a prompted Autorater to a given test set, by leveraging
  historical ratings on the test set to construct in-context learning (ICL) examples.
  We evaluate our <em>Specialist</em> method on the task of fine-grained machine translation
  evaluation, and show that it dramatically outperforms the state-of-the-art XCOMET
  metric by 54% and 119% on the WMT’23 and WMT’24 test sets, respectively. We perform
  extensive analyses to understand the representations learned by our Specialist metrics,
  and how variability in rater behavior affects their performance. We also verify
  the generalizability and robustness of our Specialist method across different numbers
  of ICL examples, LLM backbones, systems to evaluate, and evaluation tasks.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: finkelstein25a
month: 0
tex_title: 'From Jack of All Trades to Master of One: Specializing {LLM}-based Autoraters
  to a Test Set'
firstpage: 17221
lastpage: 17238
page: 17221-17238
order: 17221
cycles: false
bibtex_author: Finkelstein, Mara and Deutsch, Daniel and Riley, Parker and Juraska,
  Juraj and Kovacs, Geza and Freitag, Markus
author:
- given: Mara
  family: Finkelstein
- given: Daniel
  family: Deutsch
- given: Parker
  family: Riley
- given: Juraj
  family: Juraska
- given: Geza
  family: Kovacs
- given: Markus
  family: Freitag
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/finkelstein25a/finkelstein25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
