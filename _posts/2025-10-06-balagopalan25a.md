---
title: 'Fixing the Loose Brake: Exponential-Tailed Stopping Time in Best Arm Identification'
openreview: DF2JV03T6q
abstract: The best arm identification problem requires identifying the best alternative
  (i.e., arm) in active experimentation using the smallest number of experiments (i.e.,
  arm pulls), which is crucial for cost-efficient and timely decision-making processes.
  In the fixed confidence setting, an algorithm must stop data-dependently and return
  the estimated best arm with a correctness guarantee. Since this stopping time is
  random, we desire its distribution to have light tails. Unfortunately, many existing
  studies focus on high probability or in expectation bounds on the stopping time,
  which allow heavy tails and, for high probability bounds, even not stopping at all.
  We first prove that this never-stopping event can indeed happen for some popular
  algorithms. Motivated by this, we propose algorithms that provably enjoy an exponential-tailed
  stopping time, which improves upon the polynomial tail bound reported by Kalyanakrishnan
  et al. (2012). The first algorithm is based on a fixed budget algorithm called Sequential
  Halving along with a doubling trick. The second algorithm is a meta algorithm that
  takes in any fixed confidence algorithm with a high probability stopping guarantee
  and turns it into one that enjoys an exponential-tailed stopping time. Our results
  imply that there is much more to be desired for contemporary fixed confidence algorithms.
software: https://github.com/Kapilan-Balagopalan/Brakebooster
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: balagopalan25a
month: 0
tex_title: 'Fixing the Loose Brake: Exponential-Tailed Stopping Time in Best Arm Identification'
firstpage: 2603
lastpage: 2645
page: 2603-2645
order: 2603
cycles: false
bibtex_author: Balagopalan, Kapilan and Nguyen, Ngo Tuan and Zhao, Yao and Jun, Kwang-Sung
author:
- given: Kapilan
  family: Balagopalan
- given: Ngo Tuan
  family: Nguyen
- given: Yao
  family: Zhao
- given: Kwang-Sung
  family: Jun
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/balagopalan25a/balagopalan25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
