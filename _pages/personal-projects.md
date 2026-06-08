---
layout: single
title: "Personal Projects"
permalink: /personal-projects/
author_profile: false
---

These projects are separate from my industrial work. They are informal prototypes, tools, and paused attempts that show recurring technical interests: visualization, personal knowledge systems, sensing, ontology design, and quantum-information-inspired computation.

ArcaneArchive
------

**Status:** completed undergraduate prototype  
**Research relevance:** ontology design, domain modeling, local data management

ArcaneArchive was my undergraduate thesis project: an Android-based niche collection-management prototype for subculture fashion. I treated it as a small ontology and database design problem, translating informal community classification practices into item entities, attribute hierarchies, classification rules, and collection-management workflows.

I implemented the prototype with Kotlin, SQLite, and Android Studio, and refined the classification design through small-scale informal feedback from community members.

Classic Algorithm Beyond Classical
------

**Status:** paused research-style exploration  
**Research relevance:** quantum-information viewpoints, annealing proxies, algorithm interpretation

[Classic Algorithm Beyond Classical](https://github.com/Achernar6/Classic-Algorithm-Beyond-Classical) is an attempt to reinterpret classic algorithms from a quantum view.

The current bottleneck is choosing an appropriate annealing proxy. I previously explored a QAOA-style version, but QAOA is not a single gradually evolving physical process, and the multi-round convergence behavior was not very satisfying; in some cases it failed to converge at all. The project is now paused at the more interesting question: what kind of proxy is faithful enough to be meaningful, but still lightweight enough to be useful?

Saccharomyces-cerevisiae
------

**Status:** external open-source contribution / design support  
**Research relevance:** data visualization, user-facing analytics, reproducible summaries

[Saccharomyces-cerevisiae](https://github.com/Nyanm/Saccharomyces-cerevisiae) is an open-source score checker for **Sound Voltex Exceed Gear** with `sdvx@asphyxia` data. The repository describes it as an OpenCV and Pillow-based Python tool for generating game record images and analytical summaries.

The project can generate best-score lists, recent play records, song-specific records, and summary plots. I contributed mainly to the data-visualization side, especially ideas and design help around `gen6.plot_summary`. The code was committed through another collaborator's account, so I describe my role modestly here; the README gives special thanks to my GitHub handle for helping with the summary-plot design.

LiFlow
------

**Status:** paused prototype  
**Research relevance:** wearable sensing, cognitive-state inference, information-cost-aware work support

LiFlow is an Android watch prototype idea on the human/cognition side of Project Atlas. It is intended to support lightweight task-stack maintenance, time tracking for active tasks, and cognition-state detection during work.

The hard part is not the task timer. The hard part is inferring cognitive state from lightweight wearable signals such as heart rate and variability. I explored OpenBCI as a possible ground-truth source, but the signal quality and usability were not yet good enough for my intended workflow. I also considered EMG-based hand-movement recording as a proxy for workload analysis, but many lightweight and data-rich devices are closed-source, so the project is currently paused at the sensing and data-quality layer.

Project Atlas
------

**Status:** ongoing personal knowledge-system design  
**Research relevance:** exploration-exploitation tracking, context modeling, graph-shaped knowledge work

Project Atlas is a Logseq-based checker for **exploration-exploitation balance** in long-horizon, open-ended knowledge work. If LiFlow is the human/cognition side, Project Atlas is the project/context side.

The basic idea is to treat personal knowledge work as something that has both local task pressure and long-range research drift. I want a system that can notice whether I am over-exploiting familiar threads, over-exploring without consolidation, or losing the context that made a question meaningful in the first place.
