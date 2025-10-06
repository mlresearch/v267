---
title: 'Strategic Planning: A Top-Down Approach to Option Generation'
openreview: xkgQWEj9F2
abstract: Real-world human decision-making often relies on strategic planning, where
  <em>high-level</em> goals guide the formulation of sub-goals and subsequent actions,
  as evidenced by domains such as healthcare, business, and urban policy. Despite
  notable successes in controlled settings, conventional reinforcement learning (RL)
  follows a <em>bottom-up</em> paradigm, which can struggle to adapt to real-world
  complexities such as sparse rewards and limited exploration budgets. While methods
  like hierarchical RL and environment shaping provide partial solutions, they frequently
  rely on either ad-hoc designs (e.g. choose the set of high-level actions) or purely
  data-driven discovery of high-level actions that still requires significant exploration.
  In this paper, we introduce a <em>top-down</em> framework for RL that explicitly
  leverages <em>human-like strategy</em> to reduce sample complexity, guide exploration,
  and enable high-level decision-making. We first formalize the <em>Strategy Problem</em>,
  which frames policy generation as finding distributions over policies that balance
  <em>specificity</em> and <em>value</em>. Building on this definition, we propose
  the <em>Strategist</em> agent—an iterative framework that leverages large language
  models (LLMs) to synthesize domain knowledge into a structured representation of
  actionable strategies and sub-goals. We further develop a <em>reward shaping methodology</em>
  that translates these strategies expressed in natural language into quantitative
  feedback for RL methods. Empirically, we demonstrate a significantly faster convergence
  than conventional PPO. Taken together, our findings highlight that <em>top-down
  strategic exploration</em> opens new avenues for enhancing RL on real-world decision
  problems.
software: https://github.com/antoninbrthn/strategist
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ruiz-luyten25a
month: 0
tex_title: 'Strategic Planning: A Top-Down Approach to Option Generation'
firstpage: 52258
lastpage: 52302
page: 52258-52302
order: 52258
cycles: false
bibtex_author: Ruiz Luyten, Max and Berthon, Antonin and Van Der Schaar, Mihaela
author:
- given: Max
  family: Ruiz Luyten
- given: Antonin
  family: Berthon
- given: Mihaela
  family: Van Der Schaar
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/ruiz-luyten25a/ruiz-luyten25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
