---
permalink: /
title: "About"
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<aside class="about-profile">
  <img src="{{ '/images/avatar-jietong-li.svg' | relative_url }}" alt="Jietong Li">
  <h2>Jietong Li</h2>
  <p>Master's student, Keio University Graduate School of Media Design / Q/est Project</p>
  <p>Previous experience: ICBC Headquarters / Business R&amp;D Center; KPMG LightHouse</p>
</aside>

I graduated from the School of Software Engineering at the University of Electronic Science and Technology of China in 2024. Since then, my projects have ranged across financial knowledge graph and data systems, machine-learning pipelines, recommendation system, and LLM-based workflows.

These experiences are summarized in the pages below.

[Experience]({{ site.baseurl }}/experience/){: .btn .btn--primary }  
[Industrial Projects]({{ site.baseurl }}/industrial-projects/){: .btn }  
[Personal Projects]({{ site.baseurl }}/personal-projects/){: .btn }  
[Abilities]({{ site.baseurl }}/abilities/){: .btn }

## Research Orientation

In general, I am interested in how complex systems become learnable, computable, and diagnosable when their structure is made explicit, but not taken for granted.

A recurring lesson from my software and industry-facing work is that data rarely arrives as a clean object waiting to be modeled. It comes with implementation priors, missing relations, operational constraints, noisy labels, delayed feedback, and business contexts. **I gradually became more interested in these hidden scaffolds than in any single model family**: what should be represented, what should be ignored, and what changes when a system is forced into a particular structure.

As a result, my current interests center on the meeting point of **structure-aware machine learning** and **information-aware computation**. More broadly, I am interested in how physics and information meet through mathematics, and how this meeting can inform two accompanied questions: **how computational intelligence can act on structured reality, and how computation itself can be understood as a physical process.**

In the first direction, learning systems must face the world through representations. Real problems ask us to model constraints, encode relations, choose objectives, design losses, and decide which signals deserve to become features. Structural priors can help by preserving relations, exposing constraints, and making failure modes easier to diagnose. They can also mislead by imposing wrong locality, compressing away important signals, or making convenient assumptions look like objective structure. This is why I care about representations not only as inputs to models, but as hypotheses about the world.

In the second direction, computation itself becomes the object to be analyze. This is especially visible in newer computing paradigms where algorithms are not cleanly separated from measurement, control, noise, latency, precision, and physical resources. Information is not only fed into a procedure; it may be measured, stored, delayed, corrupted, corrected, reused, or erased. Once computation is seen this way, performance alone is no longer a sufficient description. The value of a computational process also depends on what information it acquires, what it keeps, what it discards, and what cost its feedback and control mechanisms carry.

These two directions mutually inform each other. When learning systems act on real-world structures, physical and infrastructural constraints often return as signals, bottlenecks, or oracle-like guidance. When computation is studied as a physical process, mathematical tools for representation, uncertainty, and optimization help make its behavior visible and controllable. I am interested in this seam: where structure becomes evidence, where physical or solver-generated signals become computational guidance, and where more information stops being worth its price.

My current direction is therefore diagnostic and interpretation rather than purely performance-driven. I want to understand when structural representations help learning, when they distort the problem, how external signals can guide computation without becoming opaque shortcuts, and how models or computational procedures can be evaluated by information use, stability, cost, and failure modes rather than by a single benchmark number.
