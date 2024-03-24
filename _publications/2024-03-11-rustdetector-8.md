---
title: "Understanding and Detecting Real-World Safety Issues in Rust"
collection: publications
permalink: /publication/2020-03-11-rustdetector-tse-8
excerpt: 'Our study reveals interesting real-world Rust program behaviors and new issues Rust programmers make.'
date: 2024-03-11
venue: 'IEEE Transactions on Software Engineering'
paperurl: 'https://songlh.github.io/paper/rust-tse.pdf'
citation: 'Qin, B., Chen, Y., Liu, H., Zhang, H., Wen, Q., Song, L., & Zhang, Y. (2024). IEEE Transactions on Software Engineering.'
---
Rust is a relatively new programming language designed for systems software development. Its objective is to combine the
safety guarantees typically associated with high-level languages with the performance efficiency often found in executable programs
implemented in low-level languages. The core design of Rust is a set of strict safety rules enforced through compile-time checks.
However, to support more low-level controls, Rust also allows programmers to bypass its compiler checks by writing unsafe code. As the
adoption of Rust grows in the development of safety-critical software, it becomes increasingly important to understand what safety issues
may elude Rust’s compiler checks and manifest in real Rust programs.
In this paper, we conduct a comprehensive, empirical study of Rust safety issues by close, manual inspection of 70 memory bugs, 100
concurrency bugs, and 110 programming errors leading to unexpected execution panics from five open-source Rust projects, five
widely-used Rust libraries, and two online security databases. Our study answers three important questions: what memory-safety issues
real Rust programs have, what concurrency bugs Rust programmers make, and how unexpected panics in Rust programs are caused.
Our study reveals interesting real-world Rust program behaviors and highlights new issues made by Rust programmers. Building upon
the findings of our study, we design and implement five static detectors. After being applied to the studied Rust programs and another 12
selected Rust projects, our checkers pinpoint 96 previously unknown bugs and report a negligible number of false positives, confirming
their effectiveness and the value of our empirical study

[Download paper here](https://songlh.github.io/paper/rust-tse.pdf)

Recommended citation: Qin, B., Chen, Y., Liu, H., Zhang, H., Wen, Q., Song, L., & Zhang, Y. (2024). IEEE Transactions on Software Engineering.