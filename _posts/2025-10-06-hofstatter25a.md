---
title: 'The Elicitation Game: Evaluating Capability Elicitation Techniques'
openreview: kT0EVqL77E
abstract: Capability evaluations are required to understand and regulate AI systems
  that may be deployed or further developed. Therefore, it is important that evaluations
  provide an accurate estimation of an AI system’s capabilities. However, in numerous
  cases, previously latent capabilities have been elicited from models, sometimes
  long after initial release. Accordingly, substantial efforts have been made to develop
  methods for eliciting latent capabilities from models. In this paper, we evaluate
  the effectiveness of capability elicitation techniques by intentionally training
  model organisms – language models with hidden capabilities that are revealed by
  a password. We introduce a novel method for training model organisms, based on circuit-breaking,
  which is more robust to elicitation techniques than standard password-locked models.
  We focus on elicitation techniques based on prompting and activation steering, and
  compare these to fine-tuning methods. Prompting techniques can elicit the actual
  capability of both password-locked and circuitbroken model organisms in an MCQA
  setting, while steering fails to do so. For a code-generation task, only fine-tuning
  can elicit the hidden capabilities of our novel model organism. Additionally, our
  results suggest that combining techniques improves elicitation. Still, if possible,
  fine-tuning should be the method of choice to improve the trustworthiness of capability
  evaluations.
software: https://github.com/ Felhof/sandbagging-elicitation
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hofstatter25a
month: 0
tex_title: 'The Elicitation Game: Evaluating Capability Elicitation Techniques'
firstpage: 23330
lastpage: 23356
page: 23330-23356
order: 23330
cycles: false
bibtex_author: Hofst\"{a}tter, Felix and Van Der Weij, Teun and Teoh, Jayden and Djoneva,
  Rada and Bartsch, Henning and Ward, Francis Rhys
author:
- given: Felix
  family: Hofstätter
- given: Teun
  family: Van Der Weij
- given: Jayden
  family: Teoh
- given: Rada
  family: Djoneva
- given: Henning
  family: Bartsch
- given: Francis Rhys
  family: Ward
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/hofstatter25a/hofstatter25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
