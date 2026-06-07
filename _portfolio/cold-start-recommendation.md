---
title: "Cold-Start Financial Product Recommendation for a \"What's Your MBTI?\" Mobile Bank Campaign"
excerpt: "A hybrid sparse-user recommendation workflow that used campaign labels as weak, user-facing behavioral hints, not personality science."
collection: portfolio
order: 6
---

**Context.** This project supported a youth-oriented mobile banking campaign built around a shareable "what's your MBTI?" style interaction. The campaign surface was a user-engagement hook; the modeling problem underneath was cold start. Many target users had limited investment histories, so pure collaborative filtering had limited signal.

**My contribution.** I treated the campaign labels not as validated psychological traits, but as weak self-description signals that could serve as coarse behavioral priors. I translated the playful label text into structured financial-behavior indicators, including risk preference, liquidity preference, novelty seeking, product-complexity tolerance, and likely financial goals.

I implemented metadata-based user similarity using demographic, device, and behavioral features, enabling recommendation logic for users with little or no historical product interaction. I also developed label-to-product affinity rules that connected campaign-derived signals with product categories. The goal was to make the cold-start corner less empty without pretending that a playful label was a ground-truth personality model.
