---
title: An Efficient Matrix Multiplication Algorithm for Accelerating Inference in
  Binary and Ternary Neural Networks
openreview: Nvf4jFsbv9
abstract: Despite their tremendous success and versatility, Deep Neural Networks (DNNs)
  such as Large Language Models (LLMs) suffer from inference inefficiency and rely
  on advanced computational infrastructure. To address these challenges and make these
  models more accessible and cost-effective, in this paper, we propose algorithms
  to improve the inference time and memory efficiency of DNNs with binary and ternary
  weight matrices. Particularly focusing on matrix multiplication as the bottleneck
  operation of inference, we observe that, once trained, the weight matrices of a
  model no longer change. This allows us to preprocess these matrices and create indices
  that help reduce the storage requirements by a logarithmic factor while enabling
  our efficient inference algorithms. Specifically, for a $n\times n$ weight matrix,
  our efficient algorithm guarantees a time complexity of $O(\frac{n^2}{\log n})$,
  a logarithmic factor improvement over the standard vector-matrix multiplication.
  Besides theoretical analysis, we conduct extensive experiments to evaluate the practical
  efficiency of our algorithms. Our results confirm the superiority of our approach
  both with respect to time and memory, as we observed a reduction in the multiplication
  time up to 29x and memory usage up to 6x. When applied to LLMs, our experiments
  show up to a 5.24x speedup in the inference time.
software: https://github.com/UIC-InDeXLab/RSR
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: dehghankar25a
month: 0
tex_title: An Efficient Matrix Multiplication Algorithm for Accelerating Inference
  in Binary and Ternary Neural Networks
firstpage: 12969
lastpage: 12986
page: 12969-12986
order: 12969
cycles: false
bibtex_author: Dehghankar, Mohsen and Erfanian, Mahdi and Asudeh, Abolfazl
author:
- given: Mohsen
  family: Dehghankar
- given: Mahdi
  family: Erfanian
- given: Abolfazl
  family: Asudeh
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/dehghankar25a/dehghankar25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
