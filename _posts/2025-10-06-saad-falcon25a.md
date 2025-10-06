---
title: An Architecture Search Framework for Inference-Time Techniques
openreview: EGrSMMj37o
abstract: Inference-time techniques, such as repeated sampling or iterative revisions,
  are emerging as powerful ways to enhance large-language models (LLMs) at test time.
  However, best practices for developing systems that combine these techniques remain
  underdeveloped due to our limited understanding of the utility of each technique
  across models and tasks, the interactions between them, and the massive search space
  for combining them. To address these challenges, we introduce Archon, a modular
  and automated framework for optimizing the process of selecting and combining inference-time
  techniques and LLMs. Given a compute budget and a set of available LLMs, Archon
  explores a large design space to discover optimized configurations tailored to target
  benchmarks. It can design custom or general-purpose architectures that advance the
  Pareto frontier of accuracy vs. maximum token budget compared to top-performing
  baselines. Across instruction-following, reasoning, and coding tasks, we show that
  Archon can leverage additional inference compute budget to design systems that outperform
  frontier models such as OpenAI’s o1, GPT-4o, and Claude 3.5 Sonnet by an average
  of 15.1%.
software: https://github.com/ScalingIntelligence/Archon
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: saad-falcon25a
month: 0
tex_title: An Architecture Search Framework for Inference-Time Techniques
firstpage: 52475
lastpage: 52507
page: 52475-52507
order: 52475
cycles: false
bibtex_author: Saad-Falcon, Jon and Lafuente, Adrian Gamarra and Natarajan, Shlok
  and Maru, Nahum and Todorov, Hristo and Guha, Etash Kumar and Buchanan, E. Kelly
  and Chen, Mayee F and Guha, Neel and Re, Christopher and Mirhoseini, Azalia
author:
- given: Jon
  family: Saad-Falcon
- given: Adrian Gamarra
  family: Lafuente
- given: Shlok
  family: Natarajan
- given: Nahum
  family: Maru
- given: Hristo
  family: Todorov
- given: Etash Kumar
  family: Guha
- given: E. Kelly
  family: Buchanan
- given: Mayee F
  family: Chen
- given: Neel
  family: Guha
- given: Christopher
  family: Re
- given: Azalia
  family: Mirhoseini
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/saad-falcon25a/saad-falcon25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
