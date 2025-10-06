---
title: Detecting Strategic Deception with Linear Probes
openreview: C5Jj3QKQav
abstract: AI models might use deceptive strategies as part of scheming or misaligned
  behaviour. Monitoring outputs alone is insufficient, since the AI might produce
  seemingly benign outputs while its internal reasoning is misaligned. We thus evaluate
  if linear probes can robustly detect deception by monitoring model activations.
  We test two probe-training datasets, one with contrasting instructions to be honest
  or deceptive (following Zou et al. (2023)) and one of responses to simple roleplaying
  scenarios. We test whether these probes generalize to realistic settings where Llama-3.3-70B-Instruct
  behaves deceptively, such as concealing insider trading Scheurer et al. (2023) and
  purposely underperforming on safety evaluations Benton et al. (2024). We find that
  our probe distinguishes honest and deceptive responses with AUROCs between 0.96
  and 0.999 on our evaluation datasets. If we set the decision threshold to have a
  1% false positive rate on chat data not related to deception, our probe catches
  95-99% of the deceptive responses. Overall we think white-box probes are promising
  for future monitoring systems, but current performance is insufficient as a robust
  defence against deception. Our probes’ outputs can be viewed at https://data.apolloresearch.ai/dd/
  and our code at https://github.com/ApolloResearch/deception-detection.
software: https://github.com/ApolloResearch/deception-detection
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: goldowsky-dill25a
month: 0
tex_title: Detecting Strategic Deception with Linear Probes
firstpage: 19755
lastpage: 19786
page: 19755-19786
order: 19755
cycles: false
bibtex_author: Goldowsky-Dill, Nicholas and Chughtai, Bilal and Heimersheim, Stefan
  and Hobbhahn, Marius
author:
- given: Nicholas
  family: Goldowsky-Dill
- given: Bilal
  family: Chughtai
- given: Stefan
  family: Heimersheim
- given: Marius
  family: Hobbhahn
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/goldowsky-dill25a/goldowsky-dill25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
