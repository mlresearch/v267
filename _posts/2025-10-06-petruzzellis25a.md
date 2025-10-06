---
title: Hierarchical Planning for Complex Tasks with Knowledge Graph-RAG and Symbolic
  Verification
openreview: vfqdJy12Kk
abstract: Large Language Models (LLMs) have shown promise as robotic planners but
  often struggle with long-horizon and complex tasks, especially in specialized environments
  requiring external knowledge. While hierarchical planning and Retrieval-Augmented
  Generation (RAG) address some of these challenges, they remain insufficient on their
  own and a deeper integration is required for achieving more reliable systems. To
  this end, we propose a neuro-symbolic approach that enhances LLMs-based planners
  with Knowledge Graph-based RAG for hierarchical plan generation. This method decomposes
  complex tasks into manageable subtasks, further expanded into executable atomic
  action sequences. To ensure formal correctness and proper decomposition, we integrate
  a Symbolic Validator, which also functions as a failure detector by aligning expected
  and observed world states. Our evaluation against baseline methods demonstrates
  the consistent significant advantages of integrating hierarchical planning, symbolic
  verification, and RAG across tasks of varying complexity and different LLMs. Additionally,
  our experimental setup and novel metrics not only validate our approach for complex
  planning but also serve as a tool for assessing LLMs’ reasoning and compositional
  capabilities. Code available at https://github.com/corneliocristina/HVR.
software: https://github.com/corneliocristina/HVR
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: petruzzellis25a
month: 0
tex_title: Hierarchical Planning for Complex Tasks with Knowledge Graph-{RAG} and
  Symbolic Verification
firstpage: 49105
lastpage: 49127
page: 49105-49127
order: 49105
cycles: false
bibtex_author: Petruzzellis, Flavio and Cornelio, Cristina and Lio, Pietro
author:
- given: Flavio
  family: Petruzzellis
- given: Cristina
  family: Cornelio
- given: Pietro
  family: Lio
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/petruzzellis25a/petruzzellis25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
