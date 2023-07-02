---
abstract: 'When factorized approximations are used for variational inference (VI),
  they tend to underestimate the uncertainty—as measured in various ways—of the distributions
  they are meant to approximate. We consider two popular ways to measure the uncertainty
  deficit of VI: (i) the degree to which it underestimates the componentwise variance,
  and (ii) the degree to which it underestimates the entropy. To better understand
  these effects, and the relationship between them, we examine an informative setting
  where they can be explicitly (and elegantly) analyzed: the approximation of a Gaussian, $p$,
  with a dense covariance matrix, by a Gaussian, $q$, with a diagonal covariance matrix.
  We prove that $q$ always underestimates both the componentwise variance and the
  entropy of $p$, <em>though not necessarily to the same degree</em>. Moreover we
  demonstrate that the entropy of $q$ is determined by the trade-off of two competing
  forces: it is decreased by the shrinkage of its componentwise variances (our first
  measure of uncertainty) but it is increased by the factorized approximation which
  delinks the nodes in the graphical model of $p$. We study various manifestations
  of this trade-off, notably one where, as the dimension of the problem grows, the
  per-component entropy gap between $p$ and $q$ becomes vanishingly small even though
  $q$ underestimates every componentwise variance by a constant multiplicative factor.
  We also use the shrinkage-delinkage trade-off to bound the entropy gap in terms
  of the problem dimension and the condition number of the correlation matrix of $p$.
  Finally we present empirical results on both Gaussian and non-Gaussian targets,
  the former to validate our analysis and the latter to explore its limitations.'
openreview: S18d4YiLjSV
title: 'The Shrinkage-Delinkage Trade-off: an Analysis of Factorized Gaussian Approximations
  for Variational Inference'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: margossian23a
month: 0
tex_title: 'The Shrinkage-Delinkage Trade-off: an Analysis of Factorized {G}aussian
  Approximations for Variational Inference'
firstpage: 1358
lastpage: 1367
page: 1358-1367
order: 1358
cycles: false
bibtex_author: Margossian, Charles C. and Saul, Lawrence K.
author:
- given: Charles C.
  family: Margossian
- given: Lawrence K.
  family: Saul
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
pdf: https://proceedings.mlr.press/v216/margossian23a/margossian23a.pdf
extras:
- label: Supplementary PDF
  link: https://proceedings.mlr.press/v216/margossian23a/margossian23a-supp.pdf
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
