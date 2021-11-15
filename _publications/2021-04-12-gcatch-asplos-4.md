---
title: "Automatically Detecting and Fixing Concurrency Bugs in Go Software Systems"
collection: publications
permalink: /publication/2021-04-12-gcatch-asplos-4
excerpt: 'This paper proposes static concurrency bug detection system, GCatch, and an automated concurrency bug fixing system, GFix.'
date: 2021-04-12
venue: 'ASPLOS 2021: Proceedings of the 26th ACM International Conference on Architectural Support for Programming Languages and Operating Systems 2021 Pages 616–629'
paperurl: 'https://doi.org/10.1145/3445814.3446756'
citation: 'Liu, Z., Zhu, S., Qin, B., Chen, H., & Song, L. (2021, April). Automatically detecting and fixing concurrency bugs in go software systems. In Proceedings of the 26th ACM International Conference on Architectural Support for Programming Languages and Operating Systems (pp. 616–629).'
---
Go is a statically typed programming language designed for efficient and reliable concurrent programming. For this purpose, Go provides lightweight goroutines and recommends passing messages using channels as a less error-prone means of thread communication. Go has become increasingly popular in recent years and has been adopted to build many important infrastructure software systems. However, a recent empirical study shows that concurrency bugs, especially those due to misuse of channels, exist widely in Go. These bugs severely hurt the reliability of Go concurrent systems. To fight Go concurrency bugs caused by misuse of channels, this paper proposes a static concurrency bug detection system, GCatch, and an automated concurrency bug fixing system, GFix. After disentangling an input Go program, GCatch models the complex channel operations in Go using a novel constraint system and applies a constraint solver to identify blocking bugs. GFix automatically patches blocking bugs detected by GCatch using Go’s channel-related language features. We apply GCatch and GFix to 21 popular Go applications, including Docker, Kubernetes, and gRPC. In total, GCatch finds 149 previously unknown blocking bugs due to misuse of channels and GFix successfully fixes 124 of them. We have reported all detected bugs and generated patches to developers. So far, developers have fixed 125 blocking misuse-of-channel bugs based on our reporting. Among them, 87 bugs are fixed by applying GFix’s patches directly.

[Download paper here](https://doi.org/10.1145/3445814.3446756)

Recommended citation: Liu, Z., Zhu, S., Qin, B., Chen, H., & Song, L. (2021, April). Automatically detecting and fixing concurrency bugs in go software systems. In Proceedings of the 26th ACM International Conference on Architectural Support for Programming Languages and Operating Systems (pp. 616–629).