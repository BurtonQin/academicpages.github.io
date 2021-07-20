---
title: "Algorithmic Profiling for Real-World Complexity Problems"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'We design a tool, ComAir, which can effectively conduct algorithmic profiling in production environment.'
date: 2021-03-22
venue: 'IEEE Transactions on Software Engineering, Early Access'
paperurl: 'https://doi.org/10.1109/TSE.2021.3067652'
citation: 'Qin, B., Tu, T., Liu, Z., Yu, T., & Song, L. (2021). Algorithmic Profiling for Real-World Complexity Problems. IEEE Transactions on Software Engineering.'
---
Complexity problems are a common type of performance issues, caused by algorithmic inefficiency. Algorithmic profiling aims to automatically attribute execution complexity to an executed code construct. It can identify code constructs in superlinear complexity to facilitate performance optimizations and debugging. However, existing algorithmic profiling techniques suffer from several severe limitations, missing the opportunity to be deployed in production environment and failing to effectively pinpoint root causes for performance failures caused by complexity problems. In this paper, we design a tool, ComAir, which can effectively conduct algorithmic profiling in production environment. We propose several novel instrumentation methods to significantly lower runtime overhead and enable the production-run usage. We also design an effective ranking mechanism to help developers identify root causes of performance failures due to complexity problems. Our experimental results show that ComAir can effectively identify root causes and generate accurate profiling results in production environment, while incurring a negligible runtime overhead.

[Download paper here](https://doi.org/10.1109/TSE.2021.3067652)

Recommended citation: Qin, B., Tu, T., Liu, Z., Yu, T., & Song, L. (2021). Algorithmic Profiling for Real-World Complexity Problems. IEEE Transactions on Software Engineering.