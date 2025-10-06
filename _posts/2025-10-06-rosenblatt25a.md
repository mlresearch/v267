---
title: 'Fragments to Facts: Partial-Information Fragment Inference from LLMs'
openreview: H1jGQUjAag
abstract: 'Large language models (LLMs) can leak sensitive training data through memorization
  and membership inference attacks. Prior work has primarily focused on strong adversarial
  assumptions, including attacker access to entire samples or long, ordered prefixes,
  leaving open the question of how vulnerable LLMs are when adversaries have only
  partial, unordered sample information. For example, if an attacker knows a patient
  has "hypertension," under what conditions can they query a model fine-tuned on patient
  data to learn the patient also has "osteoarthritis?" In this paper, we introduce
  a more general threat model under this weaker assumption and show that fine-tuned
  LLMs are susceptible to these fragment-specific extraction attacks. To systematically
  investigate these attacks, we propose two data-blind methods: (1) a likelihood ratio
  attack inspired by methods from membership inference, and (2) a novel approach,
  PRISM, which regularizes the ratio by leveraging an external prior. Using examples
  from medical and legal settings, we show that both methods are competitive with
  a data-aware baseline classifier that assumes access to labeled in-distribution
  data, underscoring their robustness.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: rosenblatt25a
month: 0
tex_title: 'Fragments to Facts: Partial-Information Fragment Inference from {LLM}s'
firstpage: 52041
lastpage: 52064
page: 52041-52064
order: 52041
cycles: false
bibtex_author: Rosenblatt, Lucas and Han, Bin and Wolfe, Robert and Howe, Bill
author:
- given: Lucas
  family: Rosenblatt
- given: Bin
  family: Han
- given: Robert
  family: Wolfe
- given: Bill
  family: Howe
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/rosenblatt25a/rosenblatt25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
