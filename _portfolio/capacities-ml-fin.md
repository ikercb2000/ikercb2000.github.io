---
title: "capacities-ml-fin"
collection: portfolio
permalink: /research/projects/capacities-ml-fin/
page_class: page--research
published: true
excerpt: >-
  I'm developing a Python package for mathematical capacities (non-additive measures),
  Choquet integrals and related tools. Its focus is bringing capacity-based models
  into machine-learning workflows through scikit-learn-compatible estimators,
  alongside tools for finance and risk.
codeurl: "https://github.com/ikercb2000/capacities_ml_fin"
pypiurl: "https://pypi.org/project/capacities-ml-fin/"
docsurl: "https://ikercb2000.github.io/capacities_ml_fin/"
tags:
  - Python
  - Capacities
  - Machine learning
  - scikit-learn
---

I am developing **capacities-ml-fin**, a Python package for working with **mathematical capacities (non-additive measures)** and the different areas that use them. The idea is to bring the basic tools together in one place, with a particular focus on making them useful in machine learning.

## From capacities to machine learning

The package provides tools for defining, validating and learning capacities, computing Choquet integrals, and interpreting the importance of variables and their interactions through Shapley values and interaction indices.

Its regression and classification estimators follow the **scikit-learn API**, so they can be used within familiar pipelines, cross-validation and hyperparameter searches. I want capacity-based methods to fit naturally into those workflows, rather than require a separate way of building and evaluating models.

## Beyond machine learning

The same capacity abstractions also support tools for financial applications and non-additive risk measures, connecting the mathematical foundations with practical modelling tasks.

You can find the package on [PyPI](https://pypi.org/project/capacities-ml-fin/), explore the [source code on GitHub](https://github.com/ikercb2000/capacities_ml_fin), or read the [documentation and examples](https://ikercb2000.github.io/capacities_ml_fin/).
