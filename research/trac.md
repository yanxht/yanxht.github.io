---
layout: page
title: Tree-Aggregation of Compositional Data
permalink: /research/trac/
---

Modern high-throughput sequencing technologies provide low-cost microbiome survey data across all habitats of life at unprecedented scale. At the most granular level, the primary data consist of sparse counts of amplicon sequence variants or operational taxonomic units that are associated with taxonomic and phylogenetic group information. In this contribution, we leverage the hierarchical structure of amplicon data and propose a data-driven, parameter-free, and scalable tree-guided aggregation framework to associate microbial subcompositions with response variables of interest. The excess number of zero or low count measurements at the read level forces traditional microbiome data analysis workflows to remove rare sequencing variants or group them by a fixed taxonomic rank, such as genus or phylum, or by phylogenetic similarity. By contrast, our framework, which we call trac (tree-aggregation of compositional data), learns data-adaptive taxon aggregation levels for predictive modeling making user-defined aggregation obsolete while simultaneously integrating seamlessly into the compositional data analysis framework. We illustrate the versatility of our framework in the context of large-scale regression problems in human-gut, soil, and marine microbial ecosystems. We posit that the inferred aggregation levels provide highly interpretable taxon groupings that can help microbial ecologists gain insights into the structure and functioning of the underlying ecosystem of interest.

{% include image_nocaption.html url="/images/taxa.png" width_perc=60 align="center" %}

**Reference**<br/>
- [Bien, J., **Yan, X.**, Simpson, L. and M&uuml;ller, C. (2020). **Tree-Aggregated Predictive Modeling of Microbiome Data**. *bioRxiv 2020.09.01.277632; doi:10.1101/2020.09.01.277632*](https://www.biorxiv.org/content/10.1101/2020.09.01.277632v1)