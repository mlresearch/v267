---
title: Improving the Diffusability of Autoencoders
openreview: 2hEDcA7xy4
abstract: 'Latent diffusion models have emerged as the leading approach for generating
  high-quality images and videos, utilizing compressed latent representations to reduce
  the computational burden of the diffusion process. While recent advancements have
  primarily focused on scaling diffusion backbones and improving autoencoder reconstruction
  quality, the interaction between these components has received comparatively less
  attention. In this work, we perform a spectral analysis of modern autoencoders and
  identify inordinate high-frequency components in their latent spaces, which are
  especially pronounced in the autoencoders with a large bottleneck channel size.
  We hypothesize that this high-frequency component interferes with the coarse-to-fine
  nature of the diffusion synthesis process and hinders the generation quality. To
  mitigate the issue, we propose scale equivariance: a simple regularization strategy
  that aligns latent and RGB spaces across frequencies by enforcing scale equivariance
  in the decoder. It requires minimal code changes and only up to $20$K autoencoder
  fine-tuning steps, yet significantly improves generation quality, reducing FID by
  19% for image generation on ImageNet-1K 256x256 and FVD by at least 44% for video
  generation on Kinetics-700 17x256x256. The source code is available at https://github.com/snap-research/diffusability.'
software: https://github.com/snap-research/diffusability
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: skorokhodov25a
month: 0
tex_title: Improving the Diffusability of Autoencoders
firstpage: 55876
lastpage: 55905
page: 55876-55905
order: 55876
cycles: false
bibtex_author: Skorokhodov, Ivan and Girish, Sharath and Hu, Benran and Menapace,
  Willi and Li, Yanyu and Abdal, Rameen and Tulyakov, Sergey and Siarohin, Aliaksandr
author:
- given: Ivan
  family: Skorokhodov
- given: Sharath
  family: Girish
- given: Benran
  family: Hu
- given: Willi
  family: Menapace
- given: Yanyu
  family: Li
- given: Rameen
  family: Abdal
- given: Sergey
  family: Tulyakov
- given: Aliaksandr
  family: Siarohin
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/skorokhodov25a/skorokhodov25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
