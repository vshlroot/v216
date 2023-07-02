---
abstract: It is a remarkable fact that the same $O(\sqrt{T})$ regret rate can be achieved
  in both the Experts Problem and the Adversarial Multi-Armed Bandit problem albeit
  with a worse dependence on number of actions in the latter case. In contrast, it
  has been shown that handling online MDPs with communicating structure and bandit
  information incurs $\Omega(T^{2/3})$ regret even in the case of deterministic transitions.
  Is this the price we pay for handling communicating structure or is it because we
  also have bandit feedback? In this paper we show that with full information, online
  MDPs can still be learned at an $O(\sqrt{T})$ rate even in the presence of communicating
  structure. We first show this by proposing an efficient follow the perturbed leader
  (FPL) algorithm for the deterministic transition case. We then extend our scope
  to consider stochastic transitions where we first give an inefficient $O(\sqrt{T})$-regret
  algorithm (with a mild additional condition on the dynamics). Then we show how to
  achieve $O\left(\sqrt{\frac{T}{\alpha}}\right)$ regret rate using an oracle-efficient
  algorithm but with the additional restriction that the starting state distribution
  has mass at least $\alpha$ on each state.
openreview: qZkpbyEko0
title: 'Learning in online MDPs: is there a price for handling the communicating case?'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chandrasekaran23a
month: 0
tex_title: 'Learning in online {MDPs}: is there a price for handling the communicating
  case?'
firstpage: 293
lastpage: 302
page: 293-302
order: 293
cycles: false
bibtex_author: Chandrasekaran, Gautam and Tewari, Ambuj
author:
- given: Gautam
  family: Chandrasekaran
- given: Ambuj
  family: Tewari
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
pdf: https://proceedings.mlr.press/v216/chandrasekaran23a/chandrasekaran23a.pdf
extras:
- label: Supplementary PDF
  link: https://proceedings.mlr.press/v216/chandrasekaran23a/chandrasekaran23a-supp.pdf
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
