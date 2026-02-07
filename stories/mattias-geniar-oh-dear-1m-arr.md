# Growing a Web Monitoring Tool to $1M ARR by Building in Public

**Founder:** Mattias Geniar (with cofounder Freek)
**Product:** Oh Dear
**Revenue:** $1M ARR ($83K+ MRR)
**Source:** [IndieHackers](https://www.indiehackers.com/post/X876kKI7Olsf4YBI8FWb)

---

## Overview

Oh Dear provides comprehensive website monitoring -- crawling entire websites like search engines, reporting broken links, Lighthouse SEO and accessibility scores, certificate expiration, domain expiration, DNS changes, and application health errors. Launched eight years ago.

## Tech Stack

"Intentionally boring" architecture prioritizing reliability:
- Bare metal servers for core monitoring dispatch
- 50+ VMs across DigitalOcean, Vultr, and Amazon for global coverage
- Laravel/PHP, MySQL, Redis, and ClickHouse backend

## Growth Strategy

Paid advertising proved ineffective:
- Google Ads: "Spent a ton, no meaningful difference"
- Reddit Ads: "Worked best but still not great"

Growth came primarily through word of mouth, leveraging their existing 20-year online presence via Twitter and newsletters.

## Key Lessons

1. **Build in Public:** "Don't build in private. Don't hide what you're working on. Be vocal on social media, even if it's scary."
2. **Founder-Market Fit Matters:** Coming from managing websites and hosting infrastructure, the founders understood the problem deeply.
3. **Simplicity Over Novelty:** "Reliability is the product, so novelty would be a liability."
4. **Distribution Beats Perfect Products:** A technically perfect product unknown to users has no value.

## Pricing Model

Traditional SaaS with no freemium tier -- only a free trial. Pricing based on monitor count with no hidden premium features.
