---
abstract: 'Probabilistic dependency graphs (PDGs) are a flexible class of probabilistic
  graphical models, subsuming Bayesian Networks and Factor Graphs. They can also capture
  inconsistent beliefs, and provide a way of measuring the degree of this inconsistency.
  We present the first tractable inference algorithm for PDGs with discrete variables,
  making the asymptotic complexity of PDG inference similar that of the graphical
  models they generalize. The key components are: (1) the observation that PDG inference
  can be reduced to convex optimization with exponential cone constraints, (2) a construction
  that allows us to express these problems compactly for PDGs of boundeed treewidth,
  for which we needed to further develop the theory of PDGs, and (3) an appeal to
  interior point methods that can solve such problems in polynomial time. We verify
  the correctness and time complexity of our approach, and provide an implementation
  of it. We then evaluate our implementation, and demonstrate that it outperforms
  baseline approaches.'
openreview: Yi7Mi76HKyh
title: Inference for probabilistic dependency graphs
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: richardson23a
month: 0
tex_title: Inference for probabilistic dependency graphs
firstpage: 1741
lastpage: 1751
page: 1741-1751
order: 1741
cycles: false
bibtex_author: Richardson, Oliver E. and Halpern, Joseph Y. and De Sa, Christopher
author:
- given: Oliver E.
  family: Richardson
- given: Joseph Y.
  family: Halpern
- given: Christopher
  family: De Sa
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
pdf: https://proceedings.mlr.press/v216/richardson23a/richardson23a.pdf
extras:
- label: Supplementary PDF
  link: https://proceedings.mlr.press/v216/richardson23a/richardson23a-supp.pdf
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
