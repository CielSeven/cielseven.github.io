---
title: "Assertions for Free: Transferring Invariants from Algorithm to Implementation Proofs (Functional Pearl)"
collection: publications
category: conferences
permalink: /publication/AssertionsForFree
date: 2026-08-01
venue: 'International Conference on Functional Programming (ICFP)'
paperurl: 'https://cielseven.github.io/files/icfp2026.pdf'
authors: '<strong>Shushu Wu</strong>, Chengxi Yang, Xiwei Wu, Qinxiang Cao'
citation: 'Shushu Wu, Chengxi Yang, Xiwei Wu, and Qinxiang Cao. 2026. Assertions for Free: Transferring Invariants from Algorithm to Implementation Proofs (Functional Pearl). Proc. ACM Program. Lang. 10, ICFP, Article 296 (August 2026), 23 pages.'
---

Verifying the functional correctness of real-world code with complex algorithms can be decomposed into two layers: verifying that the concrete code refines an abstract algorithmic description, and proving the correctness of the formal description. However, in practice the two layers do not stay cleanly separated. For example, in the verification of the Knuth-Morris-Pratt (KMP) algorithm, the implementation correctness proof often re-establishes algorithm properties that have already been proved, as the concrete implementation relies on invariants that the traditional two-layer method provides no mechanism to transfer.

In this pearl, we show how a clean separation can be achieved within the two-layer method by combining two simple ideas: expressing implementation correctness as a relational Hoare quadruple, and introducing assertion annotations into the abstract program to capture key invariants. Properties established in the algorithm proof are thereby transferred directly to the implementation proof, eliminating the need to re-prove them.

We demonstrate the effectiveness of this approach through non-trivial case studies, including the Knuth-Morris-Pratt pattern-matching algorithm and the depth-first search algorithm, showing that it leads to simpler proofs and a more modular verification process.
