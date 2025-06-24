---
layout: archive
title: "Code"
permalink: /code/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Here I share insights and code from my PhD journey that may be useful to others

### dynamicDML
As part of my paper [Evaluating Program Sequences with Double Machine Learning: An Application to Labor Market Policies](https://arxiv.org/abs/2506.11960) I created a Python package for dynamic Double Machine Learning (DML). This allows to flexibly estimate counterfactual outcomes and treatment effects of sequential policies from observational data, where treatment assignment may dynamically depend on time-varying characteristics. You can install the package using `pip install dynamicDML`. Check out all ressources on the [package website](https://fmuny.github.io/dynamicDML/).


### Ordered Random Forests
At the beginning of my PhD I was involved in the development of the `orf` python package. 
The Ordered Forest flexibly estimates conditional probabilities of models with ordered categorical outcomes (so-called ordered choice models). 
It provides functions for estimating marginal effects and thus provides similar output as in standard econometric models for ordered choice. 
You can install the package using `pip install orf`. Check out all ressources on the [package website](https://orf-lab.github.io/).


### Simplified block cross-validation for time series in R
This reposiory introduces a simple cross-validation scheme for time series data in `R` which I developed as part of a term project in a class on Computational Statistics.
The procedure extends the `createTimeSlices` function from the `caret` package (Kuhn et al., 2008), which allows to manually supply indices for the construction of the cross-validation samples.
[Learn more](https://github.com/fmuny/timeseries_cv).
