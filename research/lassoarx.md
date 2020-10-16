---
layout: page
title: An Improved Online Penalty Parameter Selection Procedure for Lasso AR-X
permalink: /research/lassoarx/
---

Many recent developments in the high-dimensional statistical time series literature have centered around time-dependent applications that can be adapted to regularized least squares. Of particular interest is the lasso, which both serves to regularize and provide feature selection. The lasso requires the specification of a penalty parameter that determines the degree of sparsity to impose. The most popular penalty parameter selection approaches that respect time dependence are very computationally intensive and are not appropriate for modeling certain classes of time series. We propose enhancing a canonical time series model, the autoregressive model with exogenous variables, with a novel online penalty parameter selection procedure that takes advantage of the sequential nature of time series data to improve both computational performance and forecast accuracy relative to existing methods in both a simulation and empirical application involving macroeconomic indicators.

{% include image_nocaption.html url="/images/lasso_arx.png" width_perc=60 align="center" %}

**Reference**<br/>
[Nicholson, W. and **Yan, X.** (2020). **An Improved Online Penalty Parameter Selection Procedure for l1-Penalized Autoregressive with Exogenous Variables**. *arXiv Preprint*](http://arxiv.org/abs/2010.07594)