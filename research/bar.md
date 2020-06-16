---
layout: page
title: Bernoulli Auto Regressive Framework for Link Prediction
permalink: /research/bar/
---

{% include image_partialwidth_nocaption.html url="/images/BAR_Qt.jpg" width_perc=30 align="right" %}

We present a dynamic prediction framework for binary sequences that is based on a Bernoulli generalization of the auto-regressive process. Our approach lends itself easily to variants of the standard link prediction problem for a sequence of time dependent networks. Focusing on this dynamic network link prediction/recommendation task, we propose a novel problem that exploits additional information via a much larger sequence of auxiliary networks and has important real-world relevance. To allow discovery of links that do not exist in the available data, our model estimation framework introduces a regularization term that presents a trade-off between the conventional link prediction and this discovery task. In contrast to existing work our stochastic gradient based estimation approach is highly efficient and can scale to networks with millions of nodes. We show extensive empirical results on both actual product-usage based time dependent networks and also present results on a Reddit based data set of time dependent sentiment sequences.

**Reference**<br/>
**Yan, X.** and Bijral, A. (2020). **On a Bernoulli Autoregression Framework for Link Discovery and Prediction**. *Submitted*