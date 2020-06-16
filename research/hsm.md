---
layout: page
title: Hierarchical Sparse Modeling
permalink: /research/hsm/
---

{% include image_partialwidth_nocaption.html url="/images/hsm_algo.jpg" width_perc=30 align="right" %}

Demanding sparsity in estimated models has become a routine practice in statistics. In many situations, we wish to require that the sparsity patterns attained honor certain problem-specific constraints. *Hierarchical sparse modeling* (HSM) refers to situations in which these constraints specify that one set of parameters be set to zero whenever another is set to zero. In recent years, numerous papers have developed convex regularizers for this form of sparsity structure, which arises in many areas of statistics including interaction modeling, time series analysis, and covariance estimation. In this paper, we observe that these methods fall into two frameworks, the *group lasso* (GL) and *latent overlapping group lasso* (LOG), which have not been systematically compared in the context of HSM. The purpose of this paper is to provide a side-by-side comparison of these two frameworks for HSM in terms of their statistical properties and computational efficiency. We call special attention to GL's more aggressive shrinkage of parameters deep in the hierarchy, a property not shared by LOG. In terms of computation, we introduce a finite-step algorithm that exactly solves the proximal operator of LOG for a certain simple HSM structure; we later exploit this to develop a novel path-based block coordinate descent scheme for general HSM structures. Both algorithms greatly improve the computational performance of LOG. Finally, we compare the two methods in the context of covariance estimation, where we introduce a new sparsely-banded estimator using LOG, which we show achieves the statistical advantages of an existing GL-based method but is simpler to express and more efficient to compute.

**Reference**<br/>
- [**Yan, X.** and Bien, J. (2017). **Hierarchical Sparse Modeling: A Choice of Two Group Lasso Formulations**. *Statist. Sci. 32, no. 4, 531--560. doi:10.1214/17-STS622.*](https://arxiv.org/abs/1512.01631)
- Check out our accompanying R package [**hsm**](https://cran.r-project.org/web/packages/hsm/index.html) and [its user guide](https://cran.r-project.org/web/packages/hsm/vignettes/hsm-vignette.html).