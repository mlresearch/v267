---
title: Learnings from Scaling Visual Tokenizers for Reconstruction and Generation
openreview: MumOAOs9HY
abstract: Visual tokenization via auto-encoding empowers state-of-the-art image and
  video generative models by compressing pixels into a latent space. However, questions
  remain about how auto-encoder design impacts reconstruction and downstream generative
  performance. This work explores scaling in auto-encoders for reconstruction and
  generation by replacing the convolutional backbone with an enhanced Vision Transformer
  for Tokenization (ViTok). We find scaling the auto-encoder bottleneck correlates
  with reconstruction but exhibits a nuanced relationship with generation. Separately,
  encoder scaling yields no gains, while decoder scaling improves reconstruction with
  minimal impact on generation. As a result, we determine that scaling the current
  paradigm of auto-encoders is not effective for improving generation performance.
  Coupled with Diffusion Transformers, ViTok achieves competitive image reconstruction
  and generation performance on 256p and 512p ImageNet-1K. In videos, ViTok achieves
  SOTA reconstruction and generation performance on 16-frame 128p UCF-101.
software: https://github.com/Na-VAE/navae
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hansen-estruch25a
month: 0
tex_title: Learnings from Scaling Visual Tokenizers for Reconstruction and Generation
firstpage: 22023
lastpage: 22043
page: 22023-22043
order: 22023
cycles: false
bibtex_author: Hansen-Estruch, Philippe and Yan, David and Chuang, Ching-Yao and Zohar,
  Orr and Wang, Jialiang and Hou, Tingbo and Xu, Tao and Vishwanath, Sriram and Vajda,
  Peter and Chen, Xinlei
author:
- given: Philippe
  family: Hansen-Estruch
- given: David
  family: Yan
- given: Ching-Yao
  family: Chuang
- given: Orr
  family: Zohar
- given: Jialiang
  family: Wang
- given: Tingbo
  family: Hou
- given: Tao
  family: Xu
- given: Sriram
  family: Vishwanath
- given: Peter
  family: Vajda
- given: Xinlei
  family: Chen
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/hansen-estruch25a/hansen-estruch25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
