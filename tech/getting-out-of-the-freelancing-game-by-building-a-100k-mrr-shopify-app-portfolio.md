# Getting out of the freelancing game by building a $100k+ MRR Shopify app portfolio

**Author:** James Fleischmann
**Date:** February 6, 2025
**Source:** https://www.indiehackers.com/post/qdReVAgLjz6EpW4OrJSI

---

## Revenue Numbers

- Previous app sold for $250,000
- First app scaled to $6,500 MRR before acquisition
- Current Kaching Appz portfolio: $100,000+ MRR
- Current goal: $1,000,000 MRR by end of 2025
- Basic plan pricing: $14.99
- Scale plan pricing: $29.00
- Premium tier: $59.99
- App installs: 15,000 monthly

## Key Lessons

**Build Domain Expertise First:** Erikas leveraged his background in freelance design and prior Shopify experience, recognizing that "market knowledge is a game changer" for success in app development.

**Avoid Over-Research:** Rather than prolonged planning, he advocates rapid experimentation -- building MVPs within weeks and learning through iteration rather than extensive upfront analysis.

**Product-Led Growth:** "Shipping fast and focusing on customer feedback is the key." The company introduced a feature suggestion board that now drives most development priorities.

**Bootstrap for Freedom:** Rejecting VC funding, he emphasizes that external capital creates obligations incompatible with long-term independence and profitability goals.

**Find a Technical Cofounder:** Early contractor relationships proved inefficient; partnering with a cofounder accelerated development dramatically.

**Stay Lean:** Maintaining 90% profitability while avoiding offices, employees, and agencies preserves startup momentum and culture.

## Tech Stack

Backend and Admin:
- Ruby on Rails
- React
- PostgreSQL
- Heroku
- (Transitioning to Remix and TypeScript)

Storefront:
- Svelte (compiles to web components)
- Shopify metafields for configuration
- Shopify Functions (TypeScript)

Key Architectural Decisions:
- Web components eliminate runtime dependencies, reducing load times
- Metafield storage avoids server calls for performance
- Shopify Functions handle discounting at scale
