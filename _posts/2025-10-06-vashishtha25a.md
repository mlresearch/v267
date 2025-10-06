---
title: Teaching Transformers Causal Reasoning through Axiomatic Training
openreview: AhebPqDOMI
abstract: For text-based AI systems to interact in the real world, causal reasoning
  is an essential skill. Since interventional data is costly to generate, we study
  to what extent an agent can learn causal reasoning from passive data. Specifically,
  we consider an axiomatic training setup where an agent learns from multiple demonstrations
  of a causal axiom (or rule), rather than incorporating the axiom as an inductive
  bias or inferring it from data values. A key question is whether the agent would
  learn to generalize from the axiom demonstrations to new scenarios. For example,
  if a transformer model is trained on demonstrations of the causal transitivity axiom
  over small graphs, would it generalize to applying the transitivity axiom over large
  graphs? Our results, based on a novel axiomatic training scheme, indicate that such
  generalization is possible. We consider the task of inferring whether a variable
  causes another variable, given a causal graph structure. We find that a 67 million
  parameter transformer model, when trained on linear causal chains (along with some
  noisy variations) can generalize well to new kinds of graphs, including longer causal
  chains, causal chains with reversed order, and graphs with branching; even when
  it is not explicitly trained for such settings. Our model performs at par (or even
  better) than many larger language models such as GPT-4, Gemini Pro, and Phi-3. Overall,
  our axiomatic training framework provides a new paradigm of learning causal reasoning
  from passive data that can be used to learn arbitrary axioms, as long as sufficient
  demonstrations can be generated.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: vashishtha25a
month: 0
tex_title: Teaching Transformers Causal Reasoning through Axiomatic Training
firstpage: 60964
lastpage: 60983
page: 60964-60983
order: 60964
cycles: false
bibtex_author: Vashishtha, Aniket and Kumar, Abhinav and Pandey, Atharva and Reddy,
  Abbavaram Gowtham and Ahuja, Kabir and Balasubramanian, Vineeth N. and Sharma, Amit
author:
- given: Aniket
  family: Vashishtha
- given: Abhinav
  family: Kumar
- given: Atharva
  family: Pandey
- given: Abbavaram Gowtham
  family: Reddy
- given: Kabir
  family: Ahuja
- given: Vineeth N.
  family: Balasubramanian
- given: Amit
  family: Sharma
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/vashishtha25a/vashishtha25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
