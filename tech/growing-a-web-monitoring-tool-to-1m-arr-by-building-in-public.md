# Growing a web monitoring tool to $1M ARR by building in public

**Author:** James Fleischmann
**Date:** September 13, 2025
**Source:** https://www.indiehackers.com/post/X876kKI7Olsf4YBI8FWb

---

Mattias Geniar, founder of Oh Dear alongside cofounder Freek, shares how they built a web monitoring service from identifying a market gap. With over 20 years of software development experience and background in system administration, Geniar recognized that existing uptime monitoring tools were insufficient—they typically only checked homepages rather than entire websites.

Oh Dear evolved beyond basic monitoring to include full-site crawling similar to search engine behavior, broken link detection, Lighthouse SEO and accessibility scoring, mixed content alerts, application health error reporting, and DNS change notifications. The service launched nearly eight years ago with minimal features and gradually expanded its capabilities.

The technical infrastructure deliberately prioritizes reliability: bare metal servers handle core monitoring dispatch, over 50 virtual machines spread across Digital Ocean, Vultr, and Amazon provide worldwide coverage.

The pricing model follows traditional SaaS principles with no free tier, only a trial period. Users select plans based on monitor count with no hidden features behind premium tiers. Prices have increased gradually to match inflation and expanding features.

Growth occurred primarily through word-of-mouth rather than paid advertising. Previous attempts at Google Ads and Reddit ads showed limited effectiveness. Geniar and Freek leveraged their existing online presence built over 20 years through Twitter and newsletters.

The founders emphasize transparent development: "Don't build in private. Don't hide what you're working on. Be vocal on social media, even if it's scary."

**Revenue Numbers:**
- $1M ARR
- >$83K monthly revenue
- Thousands of clients

**Key Lessons:**
- Building solutions to problems you've personally experienced creates natural market fit
- Distribution matters as much as technical excellence
- Word-of-mouth and community trust outperform paid advertising
- Transparent development builds authentic customer relationships
- "People prefer products built by humans that they can relate to"
- Intentionally "boring" technical stacks focused on reliability serve business goals better
- Pricing transparency without hidden tiers builds customer confidence

**Tech Stack:**
Laravel, PHP, MySQL, Redis, Clickhouse, bare metal servers, 50+ VMs across Digital Ocean/Vultr/Amazon
