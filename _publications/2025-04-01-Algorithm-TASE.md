---
title: "A Formal Framework for Naturally Specifying and Verifying Sequential Algorithms"
collection: publications
category: conferences
permalink: /publication/MonadForAlgo
date: 2025-04-01
venue: 'Theoretical Aspects of Software Engineering (TASE)'
paperurl: 'https://cielseven.github.io/files/MonadForAlgorithm.pdf'
artifacturl: 'https://bitbucket.org/Wushushu/monadlib/'
authors: 'Chengxi Yang*, <strong>Shushu Wu</strong>*, Qinxiang Cao. (*Equal contributions)'
citation: 'Yang, Chengxi, Shushu Wu, and Qinxiang Cao. “A Formal Framework for Naturally Specifying and Verifying Sequential Algorithms.” In: Philipp, P., Wu, Z. (eds) Theoretical Aspects of Software Engineering. TASE 2025. Lecture Notes in Computer Science, vol 15841. Springer, Cham.'
---

Current approaches for formal verification of algorithms face important limitations. For specification, they cannot express algorithms naturally and concisely, especially for algorithms with states and flexible control flow. For verification, formal proof based on Hoare logic cannot reflect the logical structure of natural proof. To address these challenges, we introduce a formal framework for naturally specifying and verifying sequential algorithms in Coq. We use the state relation monad to integrate Coq’s expressive type system with the flexible control flow of imperative languages. It supports nondeterministic operations and customizable program states, enabling specifying algorithms at an appropriate level of abstraction. For verification, we build a Hoare logic for the monad and propose a novel two-stage proof approach that separates natural logical reasoning from mechanical composition. It reflects the logical structure of natural proof, enhancing modularity and readability. We evaluate the framework by formalizing the Depth-First Search (DFS) algorithm and verifying the Knuth-Morris-Pratt (KMP) algorithm.
