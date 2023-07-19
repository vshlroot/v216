---
abstract: We consider the problem of online reinforcement learning for the Stochastic
  Shortest Path (SSP) problem modeled as an unknown MDP with an absorbing state. We
  propose PSRL-SSP, a simple posterior sampling-based reinforcement learning algorithm
  for the SSP problem. The algorithm operates in epochs. At the beginning of each
  epoch, a sample is drawn from the posterior distribution on the unknown model dynamics,
  and the optimal policy with respect to the drawn sample is followed during that
  epoch. An epoch completes if either the  number of visits to the goal state in the
  current epoch exceeds that of the previous epoch, or the number of visits to any
  of the state-action pairs is doubled. We establish a Bayesian regret bound of $\tilde{\mathcal{O}}(B_{\ast}
  S\sqrt{AK})$, where $B_{\ast}$ is an upper bound on the expected cost of the optimal
  policy, $S$ is the size of the state space, $A$ is the size of the action space,
  and $K$ is the number of episodes. The algorithm only requires the knowledge of
  the prior distribution, and has no hyper-parameters to tune. It is the first such
  posterior sampling algorithm and outperforms numerically previously proposed optimism-based
  algorithms.
openreview: wEykzGopa2
title: Posterior sampling-based online learning for the stochastic shortest path model
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: jafarnia-jahromi23a
month: 0
tex_title: Posterior sampling-based online learning for the stochastic shortest path
  model
firstpage: 922
lastpage: 931
page: 922-931
order: 922
cycles: false
bibtex_author: Jafarnia-Jahromi, Mehdi and Chen, Liyu and Jain, Rahul and Luo, Haipeng
author:
- given: Mehdi
  family: Jafarnia-Jahromi
- given: Liyu
  family: Chen
- given: Rahul
  family: Jain
- given: Haipeng
  family: Luo
date: 2023-07-02
address:
container-title: Proceedings of the Thirty-Ninth Conference on Uncertainty in Artificial
  Intelligence
volume: '216'
genre: inproceedings
issued:
  date-parts:
  - 2023
  - 7
  - 2
pdf: https://proceedings.mlr.press/v216/jafarnia-jahromi23a/jafarnia-jahromi23a.pdf
extras:
- label: Supplementary PDF
  link: https://proceedings.mlr.press/v216/jafarnia-jahromi23a/jafarnia-jahromi23a-supp.pdf
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
