---
abstract: 'We consider the problem of maximizing submodular functions under submodular
  constraints by formulating the problem in two ways: SCSKC and DiffC. Given two submodular
  functions f and g where f is monotone, the objective of SCSKC problem is to find
  a  set S of size at most k  that maximizes f(S) under the constraint that g(S) <
  theta, for a given value of theta. The problem of DiffC focuses on finding a set
  S of size at most k such that h(S) = f(S)-g(S) is maximized. It is known that these
  problems are highly inapproximable and do not admit any constant factor multiplicative
  approximation algorithms unless NP is easy. Known approximation algorithms involve  data-dependent
  approximation factors that are not efficiently computable.  We initiate a study
  of the design of approximation algorithms where the approximation factors are efficiently
  computable. For the problem of SCSKC, we prove that the greedy algorithm produces
  a solution whose value is at least (1-1/e)f(OPT) - A, where A is the data-dependent
  additive error. For the DiffC problem, we design an algorithm that uses the SCSKC
  greedy algorithm as a subroutine. This algorithm produces a solution whose value
  is at least (1-1/e)h(OPT)-B, where B is also a data-dependent additive error. A
  salient feature of our approach is that the additive error terms can be computed
  efficiently, thus enabling us to ascertain the quality of the solutions produced.'
openreview: KuOxt09ffF3
title: Maximizing submodular functions under submodular constraints
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: padmanabhan23a
month: 0
tex_title: Maximizing submodular functions under submodular constraints
firstpage: 1618
lastpage: 1627
page: 1618-1627
order: 1618
cycles: false
bibtex_author: Padmanabhan, Madhavan R. and Zhu, Yanhui and Basu, Samik and Pavan,
  A.
author:
- given: Madhavan R.
  family: Padmanabhan
- given: Yanhui
  family: Zhu
- given: Samik
  family: Basu
- given: A.
  family: Pavan
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
pdf: https://proceedings.mlr.press/v216/padmanabhan23a/padmanabhan23a.pdf
extras:
- label: Supplementary PDF
  link: https://proceedings.mlr.press/v216/padmanabhan23a/padmanabhan23a-supp.pdf
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
