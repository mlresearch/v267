---
title: 'Looking Beyond the Top-1: Transformers Determine Top Tokens in Order'
openreview: 2B11W1Z6ID
abstract: Uncovering the inner mechanisms of Transformer models offers insights into
  how they process and represent information. In this work, we analyze the computation
  performed by Transformers in the layers after the top-1 prediction remains fixed,
  known as the “saturation event”. We expand this concept to top-k tokens, demonstrating
  that similar saturation events occur across language, vision, and speech models.
  We find that these events occur in order of the corresponding tokens’ ranking, i.e.,
  the model first decides on the top ranking token, then the second highest ranking
  token, and so on. This phenomenon seems intrinsic to the Transformer architecture,
  occurring across different variants, and even in untrained Transformers. We propose
  that these events reflect task transitions, where determining each token corresponds
  to a discrete task. We show that it is possible to predict the current task from
  hidden layer embedding, and demonstrate that we can cause the model to switch to
  the next task via intervention. Leveraging our findings, we introduce a token-level
  early-exit strategy, surpassing existing methods in balancing performance and efficiency
  and show how to exploit saturation events for better language modeling.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: lioubashevski25a
month: 0
tex_title: 'Looking Beyond the Top-1: Transformers Determine Top Tokens in Order'
firstpage: 38029
lastpage: 38048
page: 38029-38048
order: 38029
cycles: false
bibtex_author: Lioubashevski, Daria and Schlank, Tomer M. and Stanovsky, Gabriel and
  Goldstein, Ariel
author:
- given: Daria
  family: Lioubashevski
- given: Tomer M.
  family: Schlank
- given: Gabriel
  family: Stanovsky
- given: Ariel
  family: Goldstein
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/lioubashevski25a/lioubashevski25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
