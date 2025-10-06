---
title: Logits are All We Need to Adapt Closed Models
openreview: DYQW7QrOyq
abstract: Many commercial Large Language Models (LLMs) are often closed-source, limiting
  developers to prompt tuning for aligning content generation with specific applications.
  While these models currently do not provide access to token logits, we argue that
  if such access were available, it would enable more powerful adaptation techniques
  beyond prompt engineering. In this paper, we propose a token-level probability reweighting
  framework that, given access to logits and a small amount of task-specific data,
  can effectively steer black-box LLMs toward application-specific content generation.
  Our approach views next-token prediction through the lens of supervised classification.
  We show that aligning black-box LLMs with task-specific data can be formulated as
  a label noise correction problem, leading to Plugin model – an autoregressive probability
  reweighting model that operates solely on logits. We provide theoretical justification
  for why reweighting logits alone is sufficient for task adaptation. Extensive experiments
  with multiple datasets, LLMs, and reweighting models demonstrate the effectiveness
  of our method, advocating for broader access to token logits in closed-source models.
  We provide our code at this https URL.
software: https://github.com/stair-lab/plugin-llm
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hiranandani25a
month: 0
tex_title: Logits are All We Need to Adapt Closed Models
firstpage: 23261
lastpage: 23289
page: 23261-23289
order: 23261
cycles: false
bibtex_author: Hiranandani, Gaurush and Wu, Haolun and Mukherjee, Subhojyoti and Koyejo,
  Sanmi
author:
- given: Gaurush
  family: Hiranandani
- given: Haolun
  family: Wu
- given: Subhojyoti
  family: Mukherjee
- given: Sanmi
  family: Koyejo
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/hiranandani25a/hiranandani25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
