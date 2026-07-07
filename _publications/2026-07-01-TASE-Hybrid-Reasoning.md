---
title: "Intuitive Verification of Sequential Programs Using Hybrid Reasoning"
collection: publications
category: conferences
permalink: /publication/HybridReasoning
date: 2026-07-01
venue: 'Theoretical Aspects of Software Engineering (TASE)'
paperurl: 'https://cielseven.github.io/files/tase2026.pdf'
authors: '<strong>Shushu Wu</strong>, Xiwei Wu, Chengxi Yang, Qinxiang Cao'
citation: 'Shushu Wu, Xiwei Wu, Chengxi Yang, and Qinxiang Cao. Intuitive Verification of Sequential Programs Using Hybrid Reasoning. Theoretical Aspects of Software Engineering (TASE), 2026.'
---

Verifying the functional correctness of real-world code with complex algorithms requires reasoning about both implementation correctness and algorithm correctness. Implementation correctness, which relates concrete programs to abstract functional models, is inherently relational, yet is traditionally formalized using standard Hoare logic alone.

This paper proposes a hybrid reasoning approach that combines relational Hoare logic and standard Hoare logic. Our key insight is that verifying implementation correctness naturally calls for relational Hoare logic, while algorithm correctness is well-suited to standard Hoare logic. Compared to traditional verifications that rely exclusively on standard Hoare logic, our approach simplifies proofs and offers more intuitive reasoning patterns.

We demonstrate this in a setting where the concrete language is a C-like imperative language and the abstract algorithm is written in a simple nondeterministic functional language. Through case studies on binary search trees and merge sort, we show how our hybrid reasoning approach addresses challenges in verifying complex algorithms, reduces proof complexity, and enhances clarity.
