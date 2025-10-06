---
title: Softmax is not Enough (for Sharp Size Generalisation)
openreview: S4JmmpnSPy
abstract: 'A key property of reasoning systems is the ability to make sharp decisions
  on their input data. For contemporary AI systems, a key carrier of sharp behaviour
  is the softmax function, with its capability to perform differentiable query-key
  lookups. It is a common belief that the predictive power of networks leveraging
  softmax arises from "circuits" which sharply perform certain kinds of computations
  consistently across many diverse inputs. However, for these circuits to be robust,
  they would need to generalise well to arbitrary valid inputs. In this paper, we
  dispel this myth: even for tasks as simple as finding the maximum key, any learned
  circuitry must disperse as the number of items grows at test time. We attribute
  this to a fundamental limitation of the softmax function to robustly approximate
  sharp functions with increasing problem size, prove this phenomenon theoretically,
  and propose adaptive temperature as an ad-hoc technique for improving the sharpness
  of softmax at inference time.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: velickovic25a
month: 0
tex_title: Softmax is not Enough (for Sharp Size Generalisation)
firstpage: 61190
lastpage: 61211
page: 61190-61211
order: 61190
cycles: false
bibtex_author: Veli\v{c}kovi\'{c}, Petar and Perivolaropoulos, Christos and Barbero,
  Federico and Pascanu, Razvan
author:
- given: Petar
  family: Veličković
- given: Christos
  family: Perivolaropoulos
- given: Federico
  family: Barbero
- given: Razvan
  family: Pascanu
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/velickovic25a/velickovic25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
