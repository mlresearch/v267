---
title: 'Outsourced Diffusion Sampling: Efficient Posterior Inference in Latent Spaces
  of Generative Models'
openreview: 94c9hu6Fsv
abstract: 'Any well-behaved generative model over a variable $\mathbf{x}$ can be expressed
  as a deterministic transformation of an exogenous (<em>outsourced’</em>) Gaussian
  noise variable $\mathbf{z}$: $\mathbf{x}=f_\theta(\mathbf{z})$. In such a model
  (<em>eg</em>, a VAE, GAN, or continuous-time flow-based model), sampling of the
  target variable $\mathbf{x} \sim p_\theta(\mathbf{x})$ is straightforward, but sampling
  from a posterior distribution of the form $p(\mathbf{x}\mid\mathbf{y}) \propto p_\theta(\mathbf{x})r(\mathbf{x},\mathbf{y})$,
  where $r$ is a constraint function depending on an auxiliary variable $\mathbf{y}$,
  is generally intractable. We propose to amortize the cost of sampling from such
  posterior distributions with diffusion models that sample a distribution in the
  noise space ($\mathbf{z}$). These diffusion samplers are trained by reinforcement
  learning algorithms to enforce that the transformed samples $f_\theta(\mathbf{z})$
  are distributed according to the posterior in the data space ($\mathbf{x}$). For
  many models and constraints, the posterior in noise space is smoother than in data
  space, making it more suitable for amortized inference. Our method enables conditional
  sampling under unconditional GAN, (H)VAE, and flow-based priors, comparing favorably
  with other inference methods. We demonstrate the proposed <b><em>outsourced diffusion
  sampling</em></b> in several experiments with large pretrained prior models: conditional
  image generation, reinforcement learning with human feedback, and protein structure
  generation.'
software: https://github.com/HyperPotatoNeo/Outsourced_Diffusion_Sampling
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: venkatraman25a
month: 0
tex_title: 'Outsourced Diffusion Sampling: Efficient Posterior Inference in Latent
  Spaces of Generative Models'
firstpage: 61212
lastpage: 61239
page: 61212-61239
order: 61212
cycles: false
bibtex_author: Venkatraman, Siddarth and Hasan, Mohsin and Kim, Minsu and Scimeca,
  Luca and Sendera, Marcin and Bengio, Yoshua and Berseth, Glen and Malkin, Nikolay
author:
- given: Siddarth
  family: Venkatraman
- given: Mohsin
  family: Hasan
- given: Minsu
  family: Kim
- given: Luca
  family: Scimeca
- given: Marcin
  family: Sendera
- given: Yoshua
  family: Bengio
- given: Glen
  family: Berseth
- given: Nikolay
  family: Malkin
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/venkatraman25a/venkatraman25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
