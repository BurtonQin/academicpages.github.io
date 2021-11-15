---
title: "Demo: VRLifeTime -- An IDE Tool to Avoid Concurrency and Memory Bugs in Rust"
collection: publications
permalink: /publication/2020-11-09-vrlifeime-ccs-5.md
excerpt: 'We present VRLifeTime, an IDE tool that can visualize lifetime for Rust programs and help programmers avoid lifetime-related mistakes.'
date: 2020-11-09
venue: 'Demo@CCS 2020: Proceedings of the 2020 ACM SIGSAC Conference on Computer and Communications Security Pages 2085–2087'
paperurl: 'https://dl.acm.org/doi/10.1145/3372297.3420024'
citation: 'Zhang, Z., Qin, B., Chen, Y., Song, L., & Zhang, Y. (2020, November). VRLifeTime -- An IDE Tool to Avoid Concurrency and Memory Bugs in Rust. In Proceedings of the 2020 ACM SIGSAC Conference on Computer and Communications Security Pages (pp. 2085–2087).'
---
As a young programming language designed for systems software
development, Rust aims to provide safety guarantees like high-level
languages and performance efficiency like low-level languages.
Lifetime is a core concept in Rust, and it is key to both safety
checks and automated resource management conducted by the Rust
compiler. However, Rust’s lifetime rules are very complex. In reality,
it is not uncommon that Rust programmers fail to infer the correct
lifetime, causing severe concurrency and memory bugs. In this
paper, we present VRLifeTime, an IDE tool that can visualize lifetime
for Rust programs and help programmers avoid lifetime-related
mistakes. Moreover, VRLifeTime can help detect some lifetime-
related bugs (i.e., double locks) with detailed debugging information.
A demo video is available at https://youtu.be/dA-PRYhYyoo.

[Download paper here](https://doi.org/10.1145/3372297.3420024)

Recommended citation: Zhang, Z., Qin, B., Chen, Y., Song, L., & Zhang, Y. (2020, November). VRLifeTime -- An IDE Tool to Avoid Concurrency and Memory Bugs in Rust. In Proceedings of the 2020 ACM SIGSAC Conference on Computer and Communications Security Pages (pp. 2085–2087)..