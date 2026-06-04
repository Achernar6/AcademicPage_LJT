---
layout: single
title: "Personal Projects"
permalink: /personal-projects/
author_profile: true
---

Ongoing projects and attempts to showcase my interest
======

These projects are not polished "product stories." They are more like small laboratories: places where I try out tools, build odd bridges between interests, and occasionally run into very real walls.

Saccharomyces-cerevisiae
------

[Saccharomyces-cerevisiae](https://github.com/Nyanm/Saccharomyces-cerevisiae) is an open-source score checker for **Sound Voltex Exceed Gear** with `sdvx@asphyxia` data. The repository describes it as an OpenCV and Pillow-based Python application for generating game record images and analytical summaries.

The project can generate best-score lists, recent play records, song-specific records, and summary plots. I contributed mainly to the data-visualization side, especially ideas and design help around `gen6.plot_summary`. The code was committed through another collaborator's account, so I describe my role modestly here; the README gives special thanks to Achernar for helping with the summary-plot design.

LiFlow
------

LiFlow is an Android watch application idea on the human/cognition side of Project Atlas. It is intended to support lightweight task-stack maintenance, time tracking for active tasks, and cognition-state detection during work.

The hard part is not the task timer. The hard part is inferring cognitive state from lightweight wearable signals such as heart rate and variability. I bought an OpenBCI electrode cap as a possible ground-truth source, but the signal quality and usability were not yet good enough for my intended workflow. I also tried thinking through EMG-based hand-movement recording as a proxy for workload analysis, but many lightweight and data-rich devices are closed-source, which makes the project temporarily stuck in the swampy but interesting part.

Project Atlas
------

Project Atlas is a Logseq-based checker for **exploration-exploitation balance** in long-horizon, open-ended knowledge work. If LiFlow is the human/cognition side, Project Atlas is the project/context side.

The basic idea is to treat personal knowledge work as something that has both local task pressure and long-range research drift. I want a system that can notice whether I am over-exploiting familiar threads, over-exploring without consolidation, or losing the context that made a question meaningful in the first place.

Classical Algorithms Beyond Classical
------

[Classical Algorithms Beyond Classical](https://github.com/Achernar6/Classic-Algorithm-Beyond-Classical) is an attempt to reinterpret classic algorithms from a quantum view.

The current bottleneck is choosing an appropriate annealing proxy. I previously explored a QAOA-style version, but QAOA is not a single gradually evolving physical process, and the multi-round convergence behavior was not very satisfying; in some cases it failed to converge at all. The project is now paused at the more interesting question: what kind of proxy is faithful enough to be meaningful, but still lightweight enough to be useful?

ArcaneArchive
------

ArcaneArchive was my undergraduate thesis project: an Android-based niche collection management application for subculture fashion. I treated it as a small ontology and database design problem, translating informal community classification practices into item entities, attribute hierarchies, classification rules, and collection-management workflows.

I implemented the prototype with Kotlin, SQLite, and Android Studio, and refined the classification design through small-scale informal feedback from community members.
