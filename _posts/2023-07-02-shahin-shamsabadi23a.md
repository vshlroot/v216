---
abstract: Recent work has shown that an adversary can reconstruct training examples
  given access to the parameters of a deep learning image classification model. We
  show that the quality of reconstruction depends heavily on the type of activation
  functions used. In particular, we show that ReLU activations lead to much lower
  quality reconstructions compared to smooth activation functions. We explore if this
  phenomenon is a fundamental property of models with ReLU activations, or if it is
  a weakness of current attack strategies. We first study the training dynamics of
  small MLPs with ReLU activations and identify redundant model parameters that do
  not memorise training examples. Building on this, we propose our Mnemonist method,
  which is able to detect redundant model parameters, and then guide current attacks
  to focus on informative parameters to improve the quality of reconstructions of
  training examples from ReLU models.
openreview: AKTUszQKbd
title: 'Mnemonist: Locating Model Parameters that Memorize Training Examples'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: shahin-shamsabadi23a
month: 0
tex_title: 'Mnemonist: Locating Model Parameters that Memorize Training Examples'
firstpage: 1879
lastpage: 1888
page: 1879-1888
order: 1879
cycles: false
bibtex_author: Shahin Shamsabadi, Ali and Hayes, Jamie and Balle, Borja and Weller,
  Adrian
author:
- given: Ali
  family: Shahin Shamsabadi
- given: Jamie
  family: Hayes
- given: Borja
  family: Balle
- given: Adrian
  family: Weller
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
pdf: https://proceedings.mlr.press/v216/shahin-shamsabadi23a/shahin-shamsabadi23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
