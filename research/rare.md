---
layout: page
title: Rare Feature Selection in High Dimensions
permalink: /research/rare/
---

It is common in modern prediction problems for many predictor variables to be counts of rarely occurring events. This leads to design matrices in which many columns are highly sparse. The challenge posed by such "rare features" has received little attention despite its prevalence in diverse areas, ranging from natural language processing (e.g., rare words) to biology (e.g., rare species). We show, both theoretically and empirically, that not explicitly accounting for the rareness of features can greatly reduce the effectiveness of an analysis. We next propose a framework for aggregating rare features into denser features in a flexible manner that creates better predictors of the response. Our strategy leverages side information in the form of a tree that encodes feature similarity.

We apply our method to data from TripAdvisor, in which we predict the numerical rating of a hotel based on the text of the associated review.  Our method achieves high accuracy by making effective use of rare words; by contrast, the lasso is unable to identify highly predictive words if they are too rare.  A companion R package, called *rare*, implements our new estimator, using the alternating direction method of multipliers.

{% include image_partialwidth_nocaption.html url="/images/rare_tree.png" width_perc=80 align="center" %}

Reference<br/>
[**Yan, X.** and Bien, J. (2018). **Rare feature selection in high dimensions**. *Submitted*](https://arxiv.org/abs/1803.06675)

Check out our accompanying R package [**rare** on CRAN](https://cran.r-project.org/web/packages/rare/index.html) and [its user guide](https://cran.r-project.org/web/packages/rare/vignettes/rare-vignette.html).