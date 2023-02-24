---
title: Simultaneous Inference for Pairwise Graphical Models with Generalized Score
  Matching
date: '2020-01-01'
publishDate: '2022-01-04T22:18:46.284063Z'
authors:
- Ming Yu
- Varun Gupta
- Mladen Kolar
publication_types:
- '2'
abstract: Probabilistic graphical models provide a flexible yet parsimonious framework
  for modeling dependencies among nodes in networks. There is a vast literature on
  parameter estimation and consistent model selection for graphical models. However,
  in many of the applications, scientists are also interested in quantifying the uncertainty
  associated with the estimated parameters and selected models, which current literature
  has not addressed thoroughly. In this paper, we propose a novel estimator for statistical
  inference on edge parameters in pairwise graphical models based on generalized Hyvarinen
  scoring rule. Hyvarinen scoring rule is especially useful in cases where the normalizing
  constant cannot be obtained efficiently in a closed form, which is a common problem
  for graphical models, including Ising models and truncated Gaussian graphical models.
  Our estimator allows us to perform statistical inference for general graphical models
  whereas the existing works mostly focus on statistical inference for Gaussian graphical
  models where finding normalizing constant is computationally tractable. Under mild
  conditions that are typically assumed in the literature for consistent estimation,
  we prove that our proposed estimator is $sqrtn$-consistent and asymptotically normal,
  which allows us to construct confidence intervals and build hypothesis tests for
  edge parameters. Moreover, we show how our proposed method can be applied to test
  hypotheses that involve a large number of model parameters simultaneously. We illustrate
  validity of our estimator through extensive simulation studies on a diverse collection
  of data-generating processes.
featured: false
publication: '*Journal of Machine Learning Research*'
tags: [stat.ME]
links:
- name: arXiv
  url: https://arxiv.org/abs/1905.06261
- name: URL
  url: http://jmlr.org/papers/v21/19-383.html
---
