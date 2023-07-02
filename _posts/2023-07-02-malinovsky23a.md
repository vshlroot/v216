---
abstract: "Virtually all state-of-the-art methods for training supervised machine
  learning models are variants of Stochastic Gradient Descent (SGD), enhanced with
  a number of additional tricks, such as minibatching, momentum, and adaptive stepsizes.
  However, one of the most basic questions in the design of  successful SGD methods,
  one that is orthogonal to the aforementioned tricks, is the choice of the next training
  data point to be learning from. Standard variants of SGD employ a  sampling with
  replacement strategy, which means that the next training data point is sampled from
  the entire data set, often independently of all previous samples. While standard
  SGD is well understood theoretically,  virtually all widely used machine learning
  software is based on  sampling without replacement as this is often empirically
  superior. That is, the training data is randomly shuffled/permuted, either only
  once at the beginning, strategy known as random shuffling (RS), or before every
  epoch, strategy known as random reshuffling (RR),  and  training proceeds in the
  data order dictated by the shuffling.  RS and RR strategies  have for a long time
  remained beyond the reach of  theoretical analysis that would satisfactorily explain
  their success. However, very recently, Mishchenko et al. [2020] provided tight  sublinear
  convergence rates through a novel analysis, and showed that these strategies can
  improve upon standard SGD in certain regimes. Inspired by these results, we seek
  to further  improve the rates of shuffling-based methods. In particular, we show
  that it is possible to enhance them with a variance reduction mechanism, obtaining
  linear convergence rates.\tTo the best of our knowledge, our linear convergence
  rates are the best for any method based on sampling without replacement."
openreview: 33yztBWiX-t
title: 'Random Reshuffling with Variance Reduction: New Analysis and Better Rates'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: malinovsky23a
month: 0
tex_title: 'Random Reshuffling with Variance Reduction: New Analysis and Better Rates'
firstpage: 1347
lastpage: 1357
page: 1347-1357
order: 1347
cycles: false
bibtex_author: Malinovsky, Grigory and Sailanbayev, Alibek and Richt\'{a}rik, Peter
author:
- given: Grigory
  family: Malinovsky
- given: Alibek
  family: Sailanbayev
- given: Peter
  family: Richtárik
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
pdf: https://proceedings.mlr.press/v216/malinovsky23a/malinovsky23a.pdf
extras:
- label: Supplementary PDF
  link: https://proceedings.mlr.press/v216/malinovsky23a/malinovsky23a-supp.pdf
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
