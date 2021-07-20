---
title: "Understanding memory and thread safety practices and issues in real-world Rust programs"
collection: publications
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: 'Our study reveals interesting real-world Rust program behaviors and new issues Rust programmers make.'
date: 2020-06-11
venue: 'PLDI 2020: Proceedings of the 41st ACM SIGPLAN Conference on Programming Language Design and ImplementationJune 2020 Pages 763–779'
paperurl: 'https://doi.org/10.1145/3385412.3386036'
citation: 'Qin, B., Chen, Y., Yu, Z., Song, L., & Zhang, Y. (2020, June). Understanding memory and thread safety practices and issues in real-world Rust programs. In Proceedings of the 41st ACM SIGPLAN Conference on Programming Language Design and Implementation (pp. 763-779).'
---
Rust is a young programming language designed for systemssoftware development. It aims to provide safety guaranteeslike high-level languagesandperformance efficiency likelow-level languages. The core design of Rust is a set of strictsafety rules enforced by compile-time checking. To supportmore low-level controls, Rust allows programmers to bypassthese compiler checks to writeunsafecode.It is important to understand what safety issues exist inreal Rust programs and how Rust safety mechanisms impactprogramming practices. We performed the first empiricalstudy of Rust by close, manual inspection of 850 unsafe codeusages and 170 bugs in five open-source Rust projects, fivewidely-used Rust libraries, two online security databases, andthe Rust standard library. Our study answers three importantquestions: how and why do programmers write unsafe code,what memory-safety issues real Rust programs have, andwhat concurrency bugs Rust programmers make. Our studyreveals interesting real-world Rust program behaviors andnew issues Rust programmers make. Based on our studyresults, we propose several directions of building Rust bugdetectors and built two static bug detectors, both of whichrevealed previously unknown bugs.

[Download paper here](https://doi.org/10.1145/3385412.3386036)

Recommended citation: Qin, B., Chen, Y., Yu, Z., Song, L., & Zhang, Y. (2020, June). Understanding memory and thread safety practices and issues in real-world Rust programs. In Proceedings of the 41st ACM SIGPLAN Conference on Programming Language Design and Implementation (pp. 763-779).