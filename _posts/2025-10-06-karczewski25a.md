---
title: 'Devil is in the Details: Density Guidance for Detail-Aware Generation with
  Flow Models'
openreview: C8pGYyfhoF
abstract: 'Diffusion models have emerged as a powerful class of generative models,
  capable of producing high-quality images by mapping noise to a data distribution.
  However, recent findings suggest that image likelihood does not align with perceptual
  quality: high-likelihood samples tend to be smooth, while lower-likelihood ones
  are more detailed. Controlling sample density is thus crucial for balancing realism
  and detail. In this paper, we analyze an existing technique, Prior Guidance, which
  scales the latent code to influence image detail. We introduce score alignment,
  a condition that explains why this method works and show that it can be tractably
  checked for any continuous normalizing flow model. We then propose Density Guidance,
  a principled modification of the generative ODE that enables exact log-density control
  during sampling. Finally, we extend Density Guidance to stochastic sampling, ensuring
  precise log-density control while allowing controlled variation in structure or
  fine details. Our experiments demonstrate that these techniques provide fine-grained
  control over image detail without compromising sample quality. Code is available
  at https://github.com/Aalto-QuML/density-guidance.'
software: https://github.com/Aalto-QuML/density-guidance
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: karczewski25a
month: 0
tex_title: 'Devil is in the Details: Density Guidance for Detail-Aware Generation
  with Flow Models'
firstpage: 29098
lastpage: 29127
page: 29098-29127
order: 29098
cycles: false
bibtex_author: Karczewski, Rafal and Heinonen, Markus and Garg, Vikas K
author:
- given: Rafal
  family: Karczewski
- given: Markus
  family: Heinonen
- given: Vikas K
  family: Garg
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/karczewski25a/karczewski25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
