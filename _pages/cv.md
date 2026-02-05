---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Computer Science, Shanghai Jiao Tong University, Sep 2021 - Present
  * Focus: Separation Logic, Relational Hoare Logic, Algorithm Verification, Monads
  * Supervisor: Qinxiang Cao, Associate Professor
* Bachelor in Computer Science, Shanghai Jiao Tong University, Sep 2017 - June 2021
  * Thesis: Functional Correctness Verification of the Red-Black Tree and Its C Implementation
  * Supervisor: Qinxiang Cao, Associate Professor

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Research Projects
======
* **Loop Invariant Generation Based on Large Language Models**, 2025 - present

  Automatically generates separation logic invariants and abstract program fragments, supporting end-to-end automation for program refinement verification. We perform symbolic execution on C programs to obtain verification conditions and generate spatial predicate invariants using in-context learning and expert correction methods. The spatial predicates within invariants are converted into separation logic predicates with abstract data, along with corresponding abstract code fragments. This approach successfully generated valid invariants and abstract fragments for linked-list-based programs (e.g., insertions, deletions, reversals).

* **QCP: A Practical Separation Logic-based C Program Verification Tool**, 2022 - present

  Qualified C Programming Verifier (QCP) is a verification tool that integrates annotation-based automatic verification with interactive proving using Rocq. QCP performs symbolic execution on annotated C programs to generate verification conditions automatically. SMT solvers verify most conditions automatically, while remaining subgoals are proved interactively using Rocq.

* **Imperative Program Verification in Two Phases**, 2019 - 2021

  Introduced a flexible two-phase method for verifying imperative programs, which involves separating the verification process into proving the algorithm's correctness and proving the implementation refines the algorithm. We implemented an iterative version of red-black trees with lazy-tagging in Rocq, and proved the correctness of the imperative C implementation of the Red-Black Tree algorithm in Verified Software Toolchain (VST) with respect to the algorithm description.

Practical Projects
======
* **Formal Verification of LiteOS-M Operating System Kernel**, From ZGC Lab, Beijing, China, 2024 - present

  We focused on the core modules of a specific LiteOS-M kernel version, proving the refinement relationship between C programs and abstract programs within the modules using tool QCP.

* **Formal Verification of XX Microkernel Operating System**, From Industry, China, 2021 - 2023

  The system is based on a mature embedded OS with multi-core DSP optimizations. We verified the correctness of critical kernel modules using concurrent relational logic.

Teaching Service
======
* Teaching Assistant, CS1601 Discrete Mathematics, Shanghai Jiao Tong University, Fall 2024
* Teaching Assistant, [CS2612 Programming Languages and Compilers](https://jhc.sjtu.edu.cn/public/courses/CS2612/2023fall/), Shanghai Jiao Tong University, Fall 2023
* Teaching Assistant, [CS2612 Programming Languages and Compilers](https://jhc.sjtu.edu.cn/public/courses/CS2612/2022fall/), Shanghai Jiao Tong University, Fall 2022

Skills
======
* Theorem Prover: Rocq
* Programming Languages: C, C++, Python, Rust, OCaml, Haskell
* Languages: Chinese (native speaker), English (fluent)
