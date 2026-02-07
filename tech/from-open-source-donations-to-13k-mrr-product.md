# From open-source donations to $13k MRR product

**Author:** James Fleischmann
**Date:** January 24, 2026
**Source:** https://www.indiehackers.com/post/rl7FbRceFPj4ZvI0nGoV

---

Andris Reinman is the creator of Nodemailer, an open-source project used by hundreds of thousands of developers worldwide. Despite its massive reach, open source didn't generate sustainable income—donations barely covered low hundreds monthly.

About five years ago, Reinman decided to monetize his email infrastructure expertise by building EmailEngine, "a self-hosted application that lets developers access email accounts via a simple HTTP REST API instead of dealing directly with IMAP, SMTP, or vendor-specific APIs."

The company currently operates at $13k monthly recurring revenue with approximately 20% yearly growth. Revenue progression has been steady and linear rather than exponential.

**Burnout & Intentional Design**

Previously, Reinman served as CTO of a VC-funded startup for four years, experiencing severe burnout. He deliberately chose a different path: "I took my laptop to the toilet and put it under my pillow while sleeping, just in case something happened." This trauma shaped his business philosophy.

EmailEngine operates without managed hosting, enterprise sales teams, or complex customer tiers. All customers are self-serve, typically small technical teams requiring minimal support.

**Monetization Journey**

EmailEngine began as an open-source side project while Reinman maintained his day job. The monetization timeline included:

- Years 1-2: Open-source release with no commercial intent
- Year 3-4.5: Dual-licensing experiment (AGPL free version, MIT paid version)—almost no takers
- Full commercial pivot: Immediate customer acquisition

The subscription model works simply: yearly auto-renewing plans via Stripe. A single pricing tier serves all customers identically, from solo developers to large financial institutions.

**Growth Strategy: Engineering-Led Marketing**

Rather than paid advertising ("my marketing budget has always been $0"), Reinman leveraged his open-source ecosystem. Key tactics included:

- Adjacent products: Released complementary open-source tools with EmailEngine links
- Natural user migration: Nodemailer users encountering needs EmailEngine addresses
- SEO positioning: "EmailEngine vs. [competitor]" comparison articles
- Credibility inheritance: "Made by the creator of Nodemailer" provides trustworthiness

The first ~10 subscribers came from the original free project (previously named IMAP API).

**Technical Challenges**

Email protocol inconsistencies across providers proved most difficult. What works with Gmail may behave differently with Korean Naver mail hosting. Testing against regional providers is expensive or impossible without local account verification methods.

**Key Advantage**

Fifteen years maintaining Nodemailer created rare email infrastructure expertise. This deep, unglamorous domain knowledge became the primary competitive moat—competitors cannot quickly replicate that credibility foundation.

**Future Direction**

Reinman plans continued EmailEngine development with potential exploration of additional products, accelerated by AI-assisted development. A scalable email-sending solution represents a possible next project. However, he has "no plans to increase revenue beyond its current trajectory" given current lifestyle satisfaction in Eastern Europe.

**Revenue Numbers:**
- Current: $13,000 monthly recurring revenue
- Growth rate: ~20% annually
- Initial donations: Low hundreds per month
- Pre-full-time: ~$500 MRR when transitioning

**Key Lessons:**
- Open-source as distribution, not monetization: Building trust through free tools creates natural pathways to paid products
- Intentional anti-growth: Rejecting enterprise sales and growth theater creates sustainable solo-founder businesses
- Self-serve customer filtering: Avoiding demos naturally qualifies customers
- Engineering-led marketing outperforms ads
- Burnout prevention drives longevity
- Linear growth compounds: Steady 20% annual growth beats volatile scaling attempts

**Tech Stack:**
Node.js, Redis (primary database), Umso.com (homepage), Docusaurus (docs), GitHub Pages, Stripe, Claude Code
