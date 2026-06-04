---
title: "AML Detection for Certificate of Deposit Transactions"
excerpt: "Temporal and network-inspired feature engineering for AML risk detection under regulated banking infrastructure."
collection: portfolio
order: 3
---

**Context.** This ICBC project supported anti-money laundering risk detection for certificate of deposit transactions. Suspicious behavior was often not visible from isolated abnormal records; risks emerged through repeated counterparties, short-range indirect relationships, abnormal transaction frequencies, and time-windowed behavioral changes.

**My contribution.** I curated and preprocessed transaction logs, customer profile fields, and account-level behavioral data. I engineered more than 30 temporal and network-inspired features, including transaction-frequency bursts, repeated counterparties, short-range transaction chains, indirect account relationships, and time-windowed behavioral shifts.

Because introducing a dedicated graph database was not practical in the regulated production environment, selected low-hop network features were approximated inside relational databases using recursive SQL logic and time-windowed aggregation. I also supported two-stage modeling that combined unsupervised anomaly detection with supervised classification.

For compliance review, I helped create explainable case summaries, including transaction-chain visualizations, risk-feature descriptions, and threshold-sensitivity reports.
