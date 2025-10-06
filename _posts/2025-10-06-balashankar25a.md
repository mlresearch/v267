---
title: 'InfAlign: Inference-aware language model alignment'
openreview: hInfvt7c4p
abstract: Language model alignment is a critical step in training modern generative
  language models. Alignment targets to improve win rate of a sample from the aligned
  model against the base model. Today, we are increasingly using inference-time algorithms
  (e.g., Best-of-$N$ , controlled decoding, tree search) to decode from language models
  rather than standard sampling. We show that this train/test mismatch makes standard
  RLHF framework sub-optimal in view of such inference-time methods. To this end,
  we propose a framework for inference-aware alignment (InfAlign), which aims to optimize
  <em>inference-time win rate</em> of the aligned policy against the base model. We
  prove that for any inference-time decoding procedure, the optimal aligned policy
  is the solution to the standard RLHF problem with a <em>transformation</em> of the
  reward. This motivates us to provide the calibrate-and-transform RL (InfAlign-CTRL)
  algorithm to solve this problem, which involves a reward calibration step and a
  KL-regularized reward maximization step with a transformation of the calibrated
  reward. For best-of-$N$ sampling and best-of-$N$ jailbreaking, we propose specific
  transformations offering up to 3-8% improvement on inference-time win rates. Finally,
  we also show that our proposed reward calibration method is a strong baseline for
  optimizing standard win rate.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: balashankar25a
month: 0
tex_title: "{I}nf{A}lign: Inference-aware language model alignment"
firstpage: 2646
lastpage: 2672
page: 2646-2672
order: 2646
cycles: false
bibtex_author: Balashankar, Ananth and Sun, Ziteng and Berant, Jonathan and Eisenstein,
  Jacob and Collins, Michael and Hutter, Adrian and Lee, Jong and Nagpal, Chirag and
  Prost, Flavien and Sinha, Aradhana and Suresh, Ananda Theertha and Beirami, Ahmad
author:
- given: Ananth
  family: Balashankar
- given: Ziteng
  family: Sun
- given: Jonathan
  family: Berant
- given: Jacob
  family: Eisenstein
- given: Michael
  family: Collins
- given: Adrian
  family: Hutter
- given: Jong
  family: Lee
- given: Chirag
  family: Nagpal
- given: Flavien
  family: Prost
- given: Aradhana
  family: Sinha
- given: Ananda Theertha
  family: Suresh
- given: Ahmad
  family: Beirami
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/balashankar25a/balashankar25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
