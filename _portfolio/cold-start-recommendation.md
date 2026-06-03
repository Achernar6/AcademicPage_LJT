---
title: "Cold-Start Financial Product Recommendation with Campaign-Derived Behavioral Labels"
excerpt: "Hybrid recommendation for sparse users using metadata similarity and weak behavioral priors from campaign-derived self-description labels."
collection: portfolio
order: 6
---

**Context.** This ICBC project supported a Gen-Z-oriented mobile banking campaign built around shareable financial personality labels. From a modeling perspective, the key challenge was cold start: many target users had limited investment histories, making pure collaborative filtering unreliable.

**My contribution.** I treated the campaign labels not as validated psychological traits, but as weak self-description signals that could serve as coarse behavioral priors. I translated qualitative financial personality descriptions into structured financial-behavior indicators, including risk preference, liquidity preference, novelty seeking, product-complexity tolerance, and likely financial goals.

I implemented metadata-based user similarity using demographic, device, and behavioral features, enabling recommendation logic for users with little or no historical product interaction. I also developed label-to-product affinity rules that connected campaign-derived signals with product categories.

**Research relevance.** This project helped me think about sparse behavioral signals, weak priors, and deployable recommendation strategies in real financial products.
