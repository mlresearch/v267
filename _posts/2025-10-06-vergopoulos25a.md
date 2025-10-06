---
title: Automated Benchmark Generation for Repository-Level Coding Tasks
openreview: qnE2m3pIAb
abstract: 'Code Agent development is an extremely active research area, where a reliable
  performance metric is critical for tracking progress and guiding new developments.
  This demand is underscored by the meteoric rise in popularity of SWE-Bench – a benchmark
  that challenges code agents to generate patches addressing GitHub issues given the
  full repository as context. The correctness of generated patches is then evaluated
  by executing a human-written test suite extracted from the repository after the
  issue’s resolution. However, constructing benchmarks like SWE-Bench requires substantial
  manual effort to set up historically accurate execution environments for testing.
  Crucially, this severely limits the number of considered repositories, e.g., just
  12 for SWE-Bench. Considering so few repositories, selected for their popularity
  runs the risk of leading to a distributional mismatch, i.e., the measured performance
  may not be representative of real-world scenarios running the riks of misguiding
  development efforts. In this work, we address this challenge and introduce SetUpAgent,
  a fully automated system capable of historically accurate dependency setup, test
  execution, and result parsing. Using SetUpAgent, we generate two new datasets: (i)
  SWEE-Bench an extended version of SWE-Bench encompassing hundreds of repositories,
  and (ii) SWA-Bench a benchmark focusing on applications rather than libraries. Comparing
  these datasets to SWE-Bench with respect to their characteristics and code agent
  performance, we find significant distributional differences, including lower issue
  description quality and detail level, higher fix complexity, and most importantly
  up to 60% lower agent success rates.'
software: https://huggingface.co/datasets/LogicStar/SWA-Bench
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: vergopoulos25a
month: 0
tex_title: Automated Benchmark Generation for Repository-Level Coding Tasks
firstpage: 61240
lastpage: 61265
page: 61240-61265
order: 61240
cycles: false
bibtex_author: Vergopoulos, Konstantinos and Mueller, Mark Niklas and Vechev, Martin
author:
- given: Konstantinos
  family: Vergopoulos
- given: Mark Niklas
  family: Mueller
- given: Martin
  family: Vechev
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/vergopoulos25a/vergopoulos25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
