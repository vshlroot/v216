---
abstract: The pre-training and fine-tuning paradigm has contributed to a number of
  breakthroughs in Natural Language Processing (NLP). Instead of directly training
  on a downstream task, language models are first pre-trained on large datasets with
  cross-domain knowledge (e.g., Pile, MassiveText, etc.) and then fine-tuned on task-specific
  data (e.g., natural language generation, text summarization, etc.). Scaling the
  model and dataset size has helped improve the performance of LLMs, but unfortunately,
  this also lead to highly prohibitive computational costs. Pre-training LLMs often
  require orders of magnitude more FLOPs than fine-tuning and the model capacity often
  remains the same between the two phases. To achieve training efficiency w.r.t training
  FLOPs, we propose to decouple the model capacity between the two phases and introduce
  Sparse Pre-training and Dense Fine-tuning (SPDF). In this work, we show the benefits
  of using unstructured weight sparsity to train only a subset of weights during pre-training
  (Sparse Pre-training) and then recover the representational capacity by allowing
  the zeroed weights to learn (Dense Fine-tuning). We demonstrate that we can induce
  up to 75% sparsity into a 1.3B parameter GPT-3 XL model resulting in a 2.5x reduction
  in pre-training FLOPs, without a significant loss in accuracy on the downstream
  tasks relative to the dense baseline. By rigorously evaluating multiple downstream
  tasks, we also establish a relationship between sparsity, task complexity and dataset
  size. Our work presents a promising direction to train large GPT models at a fraction
  of the training FLOPs using weight sparsity, while retaining the benefits of pre-trained
  textual representations for downstream tasks.
openreview: sYTDZJ-AVc
title: 'SPDF: Sparse Pre-training and Dense Fine-tuning for Large Language Models'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: thangarasa23a
month: 0
tex_title: "{SPDF}: Sparse Pre-training and Dense Fine-tuning for Large Language Models"
firstpage: 2134
lastpage: 2146
page: 2134-2146
order: 2134
cycles: false
bibtex_author: Thangarasa, Vithursan and Gupta, Abhay and Marshall, William and Li,
  Tianda and Leong, Kevin and DeCoste, Dennis and Lie, Sean and Saxena, Shreyas
author:
- given: Vithursan
  family: Thangarasa
- given: Abhay
  family: Gupta
- given: William
  family: Marshall
- given: Tianda
  family: Li
- given: Kevin
  family: Leong
- given: Dennis
  family: DeCoste
- given: Sean
  family: Lie
- given: Shreyas
  family: Saxena
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
pdf: https://proceedings.mlr.press/v216/thangarasa23a/thangarasa23a.pdf
extras:
- label: Supplementary PDF
  link: https://proceedings.mlr.press/v216/thangarasa23a/thangarasa23a-supp.pdf
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
