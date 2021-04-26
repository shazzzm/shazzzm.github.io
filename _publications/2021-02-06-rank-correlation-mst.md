---
title: "Construction of minimum spanning trees from financial returns using rank correlation"
collection: publications
permalink: /publication/2021-02-06-rank-correlation
excerpt: ""
date: 2021-05-08 14:00:00 +0000
venue: 'Physica A: Statistical Mechanics and its Applications'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0378437120309031'
citation: 'Tristan Millington, Mahesan Niranjan,
Construction of minimum spanning trees from financial returns using rank correlation,
Physica A: Statistical Mechanics and its Applications,
Volume 566,
2021,
125605,
ISSN 0378-4371,
https://doi.org/10.1016/j.physa.2020.125605.'
---
Abstract: The construction of minimum spanning trees (MSTs) from correlation matrices is an often used method to study relationships in the financial markets. However most of the work on this topic tends to use the Pearson correlation coefficient, which relies on the assumption of normality and can be brittle to the presence of outliers, neither of which is ideal for the study of financial returns. In this paper we study the inference of MSTs from daily US, UK and German financial returns using Pearson and two rank correlation methods, Spearman and Kendall’s τ. MSTs constructed using these rank methods tend to be more stable and maintain more edges over the dataset than those constructed using Pearson correlation. The edge agreement between the Pearson and rank MSTs varies significantly depending on the state of the markets, but the rank MSTs generally show strong agreement at all times. Deviation from univariate normality can be related to changes in the correlation matrices but is more difficult to connect to changes in the MSTs. Irrelevant of coefficient, the trees tend to have similar topologies. Portfolios constructed from the MST correlation matrices have a smaller turnover than those from the full covariance matrix for the larger markets, but not for the smaller German market. Using a bootstrap method we find that the correlation matrices constructed using the rank correlations are more robust, but there is little difference between the robustness of the MSTs.
Keywords: Networks; Correlation; Finance; Minimum spanning trees
[Download paper here](https://www.sciencedirect.com/science/article/abs/pii/S0378437120309031)
[Code](https://github.com/shazzzm/rank_correlation_msts)
