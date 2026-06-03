---
title: "Privacy-Preserving Synthetic Data Generation for Cross-Industry Marketing"
excerpt: "Sequential transaction feature preparation, TimeGAN-style synthetic generation, and governance-aware validation for bank-partner collaboration."
collection: portfolio
order: 4
---

**Context.** This ICBC project explored synthetic sequential transaction data as a practical alternative to raw-data sharing in a bank-partner marketing collaboration with companies such as Meituan. The goal was to support cross-industry customer analysis while avoiding direct exposure of raw transaction records, personal identifiers, and sensitive behavioral patterns.

**My contribution.** I engineered user-level, merchant-level, and transaction-sequence features, including partner-related transaction labels, demographic segments, customer activity patterns, and temporal indicators suitable for sequence modeling. I helped prepare sequential datasets and configure the input pipeline for TimeGAN-style generation.

I supported experiments with differential-privacy-inspired controls, including privacy-budget tracking and noise-based protection mechanisms, while final privacy parameters and release decisions remained subject to governance and model-risk review. I also contributed to synthetic data validation through distributional similarity metrics such as Jensen-Shannon divergence and downstream task-utility checks.

**Research relevance.** This project exposed me to the practical tension between cross-institutional collaboration, privacy protection, model utility, and deployable governance workflows.
