---
title: 'Behavioral Exploration: Learning to Explore via In-Context Adaptation'
openreview: tlLkY9E2bZ
abstract: 'Developing autonomous agents that quickly explore an environment and adapt
  their behavior online is a canonical challenge in robotics and machine learning.
  While humans are able to achieve such fast online exploration and adaptation, often
  acquiring new information and skills in only a handful of interactions, existing
  algorithmic approaches tend to rely on random exploration and slow, gradient-based
  behavior updates. How can we endow autonomous agents with such capabilities on par
  with humans? Taking inspiration from recent progress on both in-context learning
  and large-scale behavioral cloning, in this work we propose behavioral exploration:
  training agents to internalize what it means to explore and adapt in-context over
  the space of ”expert” behaviors. To achieve this, given access to a dataset of expert
  demonstrations, we train a long-context generative model to predict expert actions
  conditioned on a context of past observations and a measure of how ”exploratory”
  the expert’s behaviors are relative to this context. This enables the model to not
  only mimic the behavior of an expert, but also, by feeding its past history of interactions
  into its context, to select different expert behaviors than what have been previously
  selected, thereby allowing for fast online adaptation and targeted, ”expert-like”
  exploration. We demonstrate the effectiveness of our method in both simulated locomotion
  and manipulation settings, as well as on real-world robotic manipulation tasks,
  illustrating its ability to learn adaptive, exploratory behavior.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: wagenmaker25a
month: 0
tex_title: 'Behavioral Exploration: Learning to Explore via In-Context Adaptation'
firstpage: 61885
lastpage: 61912
page: 61885-61912
order: 61885
cycles: false
bibtex_author: Wagenmaker, Andrew and Zhou, Zhiyuan and Levine, Sergey
author:
- given: Andrew
  family: Wagenmaker
- given: Zhiyuan
  family: Zhou
- given: Sergey
  family: Levine
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/wagenmaker25a/wagenmaker25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
