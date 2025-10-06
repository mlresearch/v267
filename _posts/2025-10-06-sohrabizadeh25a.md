---
title: 'Nemotron-CORTEXA: Enhancing LLM Agents for Software Engineering Tasks via
  Improved Localization and Solution Diversity'
openreview: k6p8UKRdH7
abstract: Large Language Models (LLMs) have demonstrated significant potential in
  code generation by following natural language instructions. Unfortunately, crucial
  real-world software engineering tasks, such as debugging or repository-level feature
  implementation, involve processing extensive contexts beyond current LLM context
  sizes and performing complex reasoning that is brittle using standard autoregressive
  decoding. Enhancing LLMs’ performance in these scenarios requires careful consideration
  of the contextual information provided to the model, optimizing how the model leverages
  that, and identifying tools that enable more effective navigation of the development
  environment. To address these challenges, we introduce Nemotron-CORTEXA, an agentic
  system built on a predefined scaffold that enhances LLMs’ ability to navigate and
  reason efficiently in complex software engineering contexts. Specifically, we develop
  a novel code embedding model that retrieves the most relevant files with greater
  precision, along with a localization agent that refines the granularity of the retrieval
  process. Additionally, we demonstrate that providing diverse contextual information
  and utilizing different prompt formats enable the model to identify and resolve
  issues more efficiently. We evaluate Nemotron-CORTEXA using SWE-bench, a benchmark
  derived from real-world GitHub issues. Compared to the widely used Agentless framework,
  Nemotron-CORTEXA achieves a higher issue resolution rate at a lower cost, highlighting
  its practical impact in addressing real-world software engineering challenges.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sohrabizadeh25a
month: 0
tex_title: 'Nemotron-{CORTEXA}: Enhancing {LLM} Agents for Software Engineering Tasks
  via Improved Localization and Solution Diversity'
firstpage: 56085
lastpage: 56100
page: 56085-56100
order: 56085
cycles: false
bibtex_author: Sohrabizadeh, Atefeh and Song, Jialin and Liu, Mingjie and Roy, Rajarshi
  and Lee, Chankyu and Raiman, Jonathan and Catanzaro, Bryan
author:
- given: Atefeh
  family: Sohrabizadeh
- given: Jialin
  family: Song
- given: Mingjie
  family: Liu
- given: Rajarshi
  family: Roy
- given: Chankyu
  family: Lee
- given: Jonathan
  family: Raiman
- given: Bryan
  family: Catanzaro
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/sohrabizadeh25a/sohrabizadeh25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
