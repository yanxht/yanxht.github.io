---
layout: page
title: Attributing Change Impact in Cloud Systems with Aegis
permalink: /research/aegis/
---

Modern cloud control plane infrastructure like Microsoft Azure has evolved into a complex one to serve customer needs for diverse types of services and adequate cloud-based resources. On such interconnected system, implementing changes at one component can have an impact on other components, even across different hierarchical computing layers. As a result of the complexity and interconnected nature of the cloud-based services, it poses a challenge to correctly attribute service quality degradation to a control plane change, to infer causality between the two and to mitigate any negative impact. 

In this paper, we present Aegis, an end-to-end analytical service for attributing control plane change impact across computing layers and service components in large-scale real-world cloud systems. Aegis processes and correlates service health signals and control plane changes across components to construct the most probable causal relationship. Aegis at its core leverages a domain knowledge driven correlation algorithm to attribute platform signals to changes, and a counterfactual projection model to quantify control plane change impact to customers. Aegis can mitigate the impact of bad changes by alerting service team and recommending pausing the bad ones. 

Since Aegis’ inception in Azure Control Plane, it has caught several bad changes across service components and layers, and promptly paused them to guard the quality of service. Aegis achieves precision and recall around 80% on real-world control plane deployments.

Here is a [media coverage](https://www.msra.cn/zh-cn/news/features/icse-2023) of Aegis with screenshot pasted below.

{% include image_nocaption.html url="/images/aegis_msra_blog.png" width_perc=80 align="center" %}

Along with the paper, we published a [patent](https://www.freepatentsonline.com/y2024/0069999.html) with USPTO in February 2024:

{% include image_nocaption.html url="/images/aegis_patent.jpg" width_perc=80 align="center" %}


**Reference**<br/>
- [**Yan, X.** et al. (2023). **Aegis: Attribution of Control Plane Change Impact across Layers and Components for Cloud Systems**. *Proceedings of the 45th International Conference on Software Engineering*](https://www.microsoft.com/en-us/research/publication/aegis-attribution-of-control-plane-change-impact-across-layers-and-components-for-cloud-systems/)
- [**Yan, X.** et al. (2024). **Detecting and Mitigating Cross-Layer Impact of Change Events on A Cloud Computing System**. *United States Patent App. 17/900,640*](https://www.freepatentsonline.com/y2024/0069999.html)

