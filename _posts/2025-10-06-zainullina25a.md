---
title: Guided Search Strategies in Non-Serializable Environments with Applications
  to Software Engineering Agents
openreview: NMdWQXosFs
abstract: 'Large language models (LLMs) have recently achieved remarkable results
  in complex multi-step tasks, such as mathematical reasoning and agentic software
  engineering. However, they often struggle to maintain consistent performance across
  multiple solution attempts. One effective approach to narrow the gap between average-case
  and best-case performance is guided test-time search, which explores multiple solution
  paths to identify the most promising one. Unfortunately, effective search techniques
  (e.g. MCTS) are often unsuitable for <em>non-serializable</em> RL environments,
  such as Docker containers, where intermediate environment states cannot be easily
  saved and restored. We investigate two complementary search strategies applicable
  to such environments: 1-step lookahead and trajectory selection, both guided by
  a learned action-value function estimator. On the SWE-bench Verified benchmark,
  a key testbed for agentic software engineering, we find these methods to double
  the average success rate of a fine-tuned Qwen-72B model, achieving $40.8$%, the
  new state-of-the-art for open-weights models. Additionally, we show that these techniques
  are transferable to more advanced closed models, yielding similar improvements with
  GPT-4o.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: zainullina25a
month: 0
tex_title: Guided Search Strategies in Non-Serializable Environments with Applications
  to Software Engineering Agents
firstpage: 73957
lastpage: 73973
page: 73957-73973
order: 73957
cycles: false
bibtex_author: Zainullina, Karina and Golubev, Alexander and Trofimova, Maria and
  Polezhaev, Sergei and Badertdinov, Ibragim and Litvintseva, Daria and Karasik, Simon
  and Fisin, Filipp and Skvortsov, Sergei and Nekrashevich, Maksim and Shevtsov, Anton
  and Yangel, Boris
author:
- given: Karina
  family: Zainullina
- given: Alexander
  family: Golubev
- given: Maria
  family: Trofimova
- given: Sergei
  family: Polezhaev
- given: Ibragim
  family: Badertdinov
- given: Daria
  family: Litvintseva
- given: Simon
  family: Karasik
- given: Filipp
  family: Fisin
- given: Sergei
  family: Skvortsov
- given: Maksim
  family: Nekrashevich
- given: Anton
  family: Shevtsov
- given: Boris
  family: Yangel
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/zainullina25a/zainullina25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
