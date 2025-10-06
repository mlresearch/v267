---
title: Quantifying Memory Utilization with Effective State-Size
openreview: YKAnIvY5hf
abstract: 'As the space of causal sequence modeling architectures continues to grow,
  the need to develop a general framework for their analysis becomes increasingly
  important. With this aim, we draw insights from classical signal processing and
  control theory, to develop a quantitative measure of <em>memory utilization</em>:
  the internal mechanisms through which a model stores past information to produce
  future outputs. This metric, which we call <b><em>effective state-size</em></b>
  (ESS), is tailored to the fundamental class of systems with <em>input-invariant</em>
  and <em>input-varying linear operators</em>, encompassing a variety of computational
  units such as variants of attention, convolutions, and recurrences. Unlike prior
  work on memory utilization, which either relies on raw operator visualizations (e.g.
  attention maps), or simply the total <em>memory capacity</em> (i.e. cache size)
  of a model, our metrics provide highly interpretable and actionable measurements.
  In particular, we show how ESS can be leveraged to improve initialization strategies,
  inform novel regularizers and advance the performance-efficiency frontier through
  model distillation. Furthermore, we demonstrate that the effect of context delimiters
  (such as end-of-speech tokens) on ESS highlights cross-architectural differences
  in how large language models utilize their available memory to recall information.
  Overall, we find that ESS provides valuable insights into the dynamics that dictate
  memory utilization, enabling the design of more efficient and effective sequence
  models.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: parnichkun25a
month: 0
tex_title: Quantifying Memory Utilization with Effective State-Size
firstpage: 48276
lastpage: 48334
page: 48276-48334
order: 48276
cycles: false
bibtex_author: Parnichkun, Rom and Tumma, Neehal and Thomas, Armin W and Moro, Alessandro
  and An, Qi and Suzuki, Taiji and Yamashita, Atsushi and Poli, Michael and Massaroli,
  Stefano
author:
- given: Rom
  family: Parnichkun
- given: Neehal
  family: Tumma
- given: Armin W
  family: Thomas
- given: Alessandro
  family: Moro
- given: Qi
  family: An
- given: Taiji
  family: Suzuki
- given: Atsushi
  family: Yamashita
- given: Michael
  family: Poli
- given: Stefano
  family: Massaroli
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/parnichkun25a/parnichkun25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
