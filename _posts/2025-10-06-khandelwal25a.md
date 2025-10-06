---
title: 'FlexiClip: Locality-Preserving Free-Form Character Animation'
openreview: xtxCM4XZ82
abstract: 'Animating clipart images with seamless motion while maintaining visual
  fidelity and temporal coherence presents significant challenges. Existing methods,
  such as AniClipart, effectively model spatial deformations but often fail to ensure
  smooth temporal transitions, resulting in artifacts like abrupt motions and geometric
  distortions. Similarly, text-to-video (T2V) and image-to-video (I2V) models struggle
  to handle clipart due to the mismatch in statistical properties between natural
  video and clipart styles. This paper introduces FlexiClip, a novel approach designed
  to overcome these limitations by addressing the intertwined challenges of temporal
  consistency and geometric integrity. FlexiClip extends traditional Bézier curve-based
  trajectory modeling with key innovations: temporal Jacobians to correct motion dynamics
  incrementally, continuous-time modeling via probability flow ODEs (pfODEs) to mitigate
  temporal noise, and a flow matching loss inspired by GFlowNet principles to optimize
  smooth motion transitions. These enhancements ensure coherent animations across
  complex scenarios involving rapid movements and non-rigid deformations. Extensive
  experiments validate the effectiveness of FlexiClip in generating animations that
  are not only smooth and natural but also structurally consistent across diverse
  clipart types, including humans and animals. By integrating spatial and temporal
  modeling with pre-trained video diffusion models, FlexiClip sets a new standard
  for high-quality clipart animation, offering robust performance across a wide range
  of visual content. Project Page: https://creative-gen.github.io/flexiclip.github.io/'
software: https://creative-gen.github.io/flexiclip.github.io/
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: khandelwal25a
month: 0
tex_title: "{F}lexi{C}lip: Locality-Preserving Free-Form Character Animation"
firstpage: 29784
lastpage: 29798
page: 29784-29798
order: 29784
cycles: false
bibtex_author: Khandelwal, Anant
author:
- given: Anant
  family: Khandelwal
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/khandelwal25a/khandelwal25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
