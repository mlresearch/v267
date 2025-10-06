---
title: Aligning LLMs by Predicting Preferences from User Writing Samples
openreview: eUMGCipgtE
abstract: 'Accommodating human preferences is essential for creating aligned LLM agents
  that deliver personalized and effective interactions. Recent work has shown the
  potential for LLMs acting as writing agents to infer a description of user preferences.
  Agent alignment then comes from conditioning on the inferred preference description.
  However, existing methods often produce generic preference descriptions that fail
  to capture the unique and individualized nature of human preferences. This paper
  introduces PROSE, a method designed to enhance the precision of preference descriptions
  inferred from user writing samples. PROSE incorporates two key elements: (1) iterative
  refinement of inferred preferences, and (2) verification of inferred preferences
  across multiple user writing samples. We evaluate PROSE with several LLMs (i.e.,
  Qwen2.5 7B and 72B Instruct, GPT-mini, and GPT-4o) on a summarization and an email
  writing task. We find that PROSE more accurately infers nuanced human preferences,
  improving the quality of the writing agent’s generations over CIPHER (a state-of-the-art
  method for inferring preferences) by 33%. Lastly, we demonstrate that ICL and PROSE
  are complementary methods, and combining them provides up to a 9% improvement over
  ICL alone. Code: https://github.com/apple/ml-predict'
software: github.com/apple/ml-predict
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: aroca-ouellette25a
month: 0
tex_title: Aligning {LLM}s by Predicting Preferences from User Writing Samples
firstpage: 1690
lastpage: 1721
page: 1690-1721
order: 1690
cycles: false
bibtex_author: Aroca-Ouellette, St\'{e}phane and Mackraz, Natalie and Theobald, Barry-John
  and Metcalf, Katherine
author:
- given: Stéphane
  family: Aroca-Ouellette
- given: Natalie
  family: Mackraz
- given: Barry-John
  family: Theobald
- given: Katherine
  family: Metcalf
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
pdf: https://raw.githubusercontent.com/mlresearch/v267/main/assets/aroca-ouellette25a/aroca-ouellette25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
