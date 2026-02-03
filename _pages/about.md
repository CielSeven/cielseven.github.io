---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div id="about" style="position: absolute; top: 0;"></div>

I am a final-year Ph.D. student in the Programming Language Group at Shanghai Jiao Tong University, supervised by Prof. Qinxiang Cao. 

My research focuses on program verification, with particular emphasis on Separation Logic and Relational Hoare Logic. I am especially interested in developing scalable, modular tools to ensure the safety and correctness of programs.

<h1 id="researchpro" style="margin-top: 2em;">Research Interests</h1>
1. **Program Verification**: separation logic, relational Hoare logic, concurrent separation logic
1. **Monads**: state monads, effect monads, interaction trees
1. **LLMs for Verification**: loop invariant generation, verification condition (VC) solving


<h1 id="publications" style="margin-top: 2em;">Publications</h1>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


