---
title: 'Avoiding Leakage Poisoning: Concept Interventions Under Distribution Shifts'
openreview: 7mxDGiF01U
abstract: In this paper, we investigate how concept-based models (CMs) respond to
  out-of-distribution (OOD) inputs. CMs are interpretable neural architectures that
  first predict a set of high-level <em>concepts</em> (e.g., "stripes", "black") and
  then predict a task label from those concepts. In particular, we study the impact
  of <em>concept interventions</em> (i.e., operations where a human expert corrects
  a CM’s mispredicted concepts at test time) on CMs’ task predictions when inputs
  are OOD. Our analysis reveals a weakness in current state-of-the-art CMs, which
  we term <em>leakage poisoning</em>, that prevents them from properly improving their
  accuracy when intervened on for OOD inputs. To address this, we introduce <em>MixCEM</em>,
  a new CM that learns to dynamically exploit leaked information missing from its
  concepts only when this information is in-distribution. Our results across tasks
  with and without complete sets of concept annotations demonstrate that MixCEMs outperform
  strong baselines by significantly improving their accuracy for both in-distribution
  and OOD samples in the presence and absence of concept interventions.
software: https://github.com/mateoespinosa/cem
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: espinosa-zarlenga25a
month: 0
tex_title: 'Avoiding Leakage Poisoning: Concept Interventions Under Distribution Shifts'
firstpage: 15564
lastpage: 15595
page: 15564-15595
order: 15564
cycles: false
bibtex_author: Espinosa Zarlenga, Mateo and Dominici, Gabriele and Barbiero, Pietro
  and Shams, Zohreh and Jamnik, Mateja
author:
- given: Mateo
  family: Espinosa Zarlenga
- given: Gabriele
  family: Dominici
- given: Pietro
  family: Barbiero
- given: Zohreh
  family: Shams
- given: Mateja
  family: Jamnik
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/espinosa-zarlenga25a/espinosa-zarlenga25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
