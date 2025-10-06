---
title: Are Sparse Autoencoders Useful? A Case Study in Sparse Probing
openreview: rNfzT8YkgO
abstract: 'Sparse autoencoders (SAEs) are a popular method for interpreting concepts
  represented in large language model (LLM) activations. However, there is a lack
  of evidence regarding the validity of their interpretations due to the lack of a
  ground truth for the concepts used by an LLM, and a growing number of works have
  presented problems with current SAEs. One alternative source of evidence would be
  demonstrating that SAEs improve performance on downstream tasks beyond existing
  baselines. We test this by applying SAEs to the real-world task of LLM activation
  probing in four regimes: data scarcity, class imbalance, label noise, and covariate
  shift. Due to the difficulty of detecting concepts in these challenging settings,
  we hypothesize that SAEs’ basis of interpretable, concept-level latents should provide
  a useful inductive bias. However, although SAEs occasionally perform better than
  baselines on individual datasets, we are unable to design ensemble methods combining
  SAEs with baselines that consistently outperform ensemble methods solely using baselines.
  Additionally, although SAEs initially appear promising for identifying spurious
  correlations, detecting poor dataset quality, and training multi-token probes, we
  are able to achieve similar results with simple non-SAE baselines as well. Though
  we cannot discount SAEs’ utility on other tasks, our findings highlight the shortcomings
  of current SAEs and the need to rigorously evaluate interpretability methods on
  downstream tasks with strong baselines.'
software: https://github.com/JoshEngels/SAE-Probing
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kantamneni25a
month: 0
tex_title: Are Sparse Autoencoders Useful? {A} Case Study in Sparse Probing
firstpage: 29018
lastpage: 29049
page: 29018-29049
order: 29018
cycles: false
bibtex_author: Kantamneni, Subhash and Engels, Joshua and Rajamanoharan, Senthooran
  and Tegmark, Max and Nanda, Neel
author:
- given: Subhash
  family: Kantamneni
- given: Joshua
  family: Engels
- given: Senthooran
  family: Rajamanoharan
- given: Max
  family: Tegmark
- given: Neel
  family: Nanda
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/kantamneni25a/kantamneni25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
