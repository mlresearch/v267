---
title: Enhancing Cooperative Multi-Agent Reinforcement Learning with State Modelling
  and Adversarial Exploration
openreview: TCsdlqzZNL
abstract: Learning to cooperate in distributed partially observable environments with
  no communication abilities poses significant challenges for multi-agent deep reinforcement
  learning (MARL). This paper addresses key concerns in this domain, focusing on inferring
  state representations from individual agent observations and leveraging these representations
  to enhance agents’ exploration and collaborative task execution policies. To this
  end, we propose a novel state modelling framework for cooperative MARL, where agents
  infer meaningful belief representations of the non-observable state, with respect
  to optimizing their own policies, while filtering redundant and less informative
  joint state information. Building upon this framework, we propose the MARL SMPE$^2$
  algorithm. In SMPE$^2$, agents enhance their own policy’s discriminative abilities
  under partial observability, explicitly by incorporating their beliefs into the
  policy network, and implicitly by adopting an adversarial type of exploration policies
  which encourages agents to discover novel, high-value states while improving the
  discriminative abilities of others. Experimentally, we show that SMPE$^2$ outperforms
  a plethora of state-of-the-art MARL algorithms in complex fully cooperative tasks
  from the MPE, LBF, and RWARE benchmarks.
software: https://github.com/ddaedalus/smpe
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kontogiannis25a
month: 0
tex_title: Enhancing Cooperative Multi-Agent Reinforcement Learning with State Modelling
  and Adversarial Exploration
firstpage: 31437
lastpage: 31466
page: 31437-31466
order: 31437
cycles: false
bibtex_author: Kontogiannis, Andreas and Papathanasiou, Konstantinos and Shen, Yi
  and Stamou, Giorgos and Zavlanos, Michael M. and Vouros, George
author:
- given: Andreas
  family: Kontogiannis
- given: Konstantinos
  family: Papathanasiou
- given: Yi
  family: Shen
- given: Giorgos
  family: Stamou
- given: Michael M.
  family: Zavlanos
- given: George
  family: Vouros
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/kontogiannis25a/kontogiannis25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
