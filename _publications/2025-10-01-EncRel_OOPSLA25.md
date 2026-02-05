---
title: "Encode the ∀∃ Relational Hoare Logic into Standard Hoare Logic"
collection: publications
category: conferences
permalink: /publication/EncRel
date: 2025-10-01
venue: 'Object-oriented Programming, Systems, Languages, and Applications (OOPSLA)'
authors: '<strong>Shushu Wu</strong>, Xiwei Wu, Qinxiang Cao'
paperurl: 'https://cielseven.github.io/files/encreltheory.pdf'
artifacturl: 'https://github.com/CielSeven/EncRelTheory'
citation: 'Shushu Wu, Xiwei Wu, and Qinxiang Cao. 2025. Encode the ∀∃ Relational Hoare Logic into Standard Hoare Logic. Proc. ACM Program. Lang. 9, OOPSLA2, Article 360 (October 2025), 28 pages.'
---
Verifying a real-world program’s functional correctness can be decomposed into (1) a refinement proof showing that the program implements a more abstract high-level program and (2) an algorithm correctness proof at the high level. 
Relational Hoare logic serves as a powerful tool to establish refinement but often necessitates formalization beyond standard Hoare logic. Particularly in the nondeterministic setting, the $$\forall\exists$$ relational Hoare logic is required.  Existing approaches encode this logic into a Hoare logic with ghost states and invariants, yet these extensions significantly increase formalization complexity and soundness proof overhead. 

This paper proposes a generic encoding theory that reduces the $$\forall\exists$$ relational Hoare logic to standard (unary) Hoare logic.  Precisely, we propose to redefine the validity of relational Hoare triples while preserving the original proof rules and then encapsulate the $\forall\exists$ pattern within assertions.  We have proved that the validity of encoded standard Hoare triples is equivalent to the validity of the desired relational Hoare triples.  Moreover, the encoding theory demonstrates how common relational Hoare logic proof rules are indeed special cases of standard Hoare logic proof rules, and relational proof steps correspond to standard proof steps. Our theory enables standard Hoare logic to prove $\forall\exists$ relational properties by defining a predicate ${\color{RoyalBlue}\mathsf{Exec}}$, without requiring modifications to the logic framework or re-verification of soundness.
