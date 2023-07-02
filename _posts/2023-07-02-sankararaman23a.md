---
abstract: We study algorithms for online  change-point detection (OCPD), where samples
  that are potentially heavy-tailed, are presented one at a time and a change in the
  underlying mean must be detected as early as possible. We present an algorithm based
  on clipped Stochastic Gradient Descent (SGD), that works even if we only assume
  that the second moment of the data generating process is bounded. We derive guarantees
  on worst-case, finite-sample false-positive rate (FPR) over the family of all distributions
  with bounded second moment. Thus, our method is the first OCPD algorithm that guarantees
  finite-sample FPR, even if the data is high dimensional and  the underlying distributions
  are heavy-tailed. The technical contribution of our paper is to show that clipped-SGD
  can estimate the mean of a random vector and simultaneously provide confidence bounds
  at all confidence values. We combine this robust estimate with a union bound argument
  and construct a sequential change-point algorithm with finite-sample FPR guarantees.
  We show empirically that our algorithm works well in a variety of situations, whether
  the underlying data are heavy-tailed, light-tailed, high dimensional or discrete.
  No other algorithm achieves bounded FPR theoretically or empirically, over all settings
  we study simultaneously.
openreview: ohlrZPTPXGK
title: Online Heavy-tailed Change-point detection
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sankararaman23a
month: 0
tex_title: Online Heavy-tailed Change-point detection
firstpage: 1815
lastpage: 1826
page: 1815-1826
order: 1815
cycles: false
bibtex_author: Sankararaman, Abishek and Narayanaswamy, Balakrishnan
author:
- given: Abishek
  family: Sankararaman
- given: Balakrishnan
  family: Narayanaswamy
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
pdf: https://proceedings.mlr.press/v216/sankararaman23a/sankararaman23a.pdf
extras:
- label: Supplementary PDF
  link: https://proceedings.mlr.press/v216/sankararaman23a/sankararaman23a-supp.pdf
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
