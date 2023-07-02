---
abstract: Supervised learning typically focuses on learning transferable representations
  from training examples annotated by humans. While rich annotations (like soft labels)
  carry more information than sparse annotations (like hard labels), they are also
  more expensive to collect. For example, while hard labels only provide information
  about the closest class an object belongs to (e.g., “this is a dog”), soft labels
  provide information about the object’s relationship with multiple classes (e.g.,
  “this is most likely a dog, but it could also be a wolf or a coyote”). We use information
  theory to compare how a number of commonly-used supervision signals contribute to
  representation-learning performance, as well as how their capacity is affected by
  factors such as the number of labels, classes, dimensions, and noise. Our framework
  provides theoretical justification for using hard labels in the big-data regime,
  but richer supervision signals for few-shot learning and out-of-distribution generalization.
  We validate these results empirically in a series of experiments with over 1 million
  crowdsourced image annotations and conduct a cost-benefit analysis to establish
  a tradeoff curve that enables users to optimize the cost of supervising representation
  learning on their own datasets.
openreview: mBkn2NgJPrv
title: On the informativeness of supervision signals
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sucholutsky23a
month: 0
tex_title: On the informativeness of supervision signals
firstpage: 2036
lastpage: 2046
page: 2036-2046
order: 2036
cycles: false
bibtex_author: Sucholutsky, Ilia and Battleday, Ruairidh M. and Collins, Katherine
  M. and Marjieh, Raja and Peterson, Joshua and Singh, Pulkit and Bhatt, Umang and
  Jacoby, Nori and Weller, Adrian and Griffiths, Thomas L.
author:
- given: Ilia
  family: Sucholutsky
- given: Ruairidh M.
  family: Battleday
- given: Katherine M.
  family: Collins
- given: Raja
  family: Marjieh
- given: Joshua
  family: Peterson
- given: Pulkit
  family: Singh
- given: Umang
  family: Bhatt
- given: Nori
  family: Jacoby
- given: Adrian
  family: Weller
- given: Thomas L.
  family: Griffiths
date: 2023-07-02
address:
container-title: Proceedings of the Thirty-Nineth Conference on Uncertainty in Artificial
  Intelligence
volume: '216'
genre: inproceedings
issued:
  date-parts:
  - 2023
  - 7
  - 2
pdf: https://proceedings.mlr.press/v216/sucholutsky23a/sucholutsky23a.pdf
extras:
- label: Supplementary PDF
  link: https://proceedings.mlr.press/v216/sucholutsky23a/sucholutsky23a-supp.pdf
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
