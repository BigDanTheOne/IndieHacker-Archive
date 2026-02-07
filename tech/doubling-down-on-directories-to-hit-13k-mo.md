# Doubling down on directories to hit $13k/mo

**Author:** James Fleischmann
**Date:** February 5, 2026
**Source:** https://www.indiehackers.com/post/2KasH9NLK3ehlTL9GeGO

---

Piotr Kulpinski built OpenAlternative, a community-driven directory of open-source alternatives to proprietary software, and Dirstarter, a Next.js boilerplate for directory websites. These two projects generate $13,000 monthly in combined revenue.

Kulpinski's journey began with a WordPress theme called Chipmunk for directory creation, which generated his first online sale—a pivotal validation moment. After years of freelancing and failed SaaS attempts, he returned to directories as his core focus.

OpenAlternative launched in February 2024 after a deliberate 48-hour sprint. Kulpinski manually compiled 70 open-source projects, prioritizing quality and active maintenance. The initial stack used Astro, Airtable, and Cloudflare Workers. The site attracted over 100,000 visitors in its first week through Reddit and Hacker News communities.

The monetization journey included a costly early mistake. After receiving 250+ upvotes on Reddit's r/SelfHosted, Kulpinski added a $97 Stripe payment link for featured listings. The community backlash was immediate—the post was removed and credibility suffered. He learned that trust-building must precede commercialization, particularly in open-source communities skeptical of commercial motives.

After pausing monetization for nearly a year, Kulpinski successfully implemented featured listings and sponsorships more thoughtfully. OpenAlternative now generates approximately $6,500 monthly through ads and sponsorships (65%) plus featured listings (35%).

When Kulpinski found himself replicating his technical setup across multiple directory projects, he recognized an opportunity and packaged it as Dirstarter—a boilerplate generating $5,000 monthly in one-time purchases. Additional revenue streams include $250 from other directories and $500 from affiliate commissions.

The evolved tech stack includes Next.js 15, PostgreSQL, Vercel hosting, Stripe payments, and Cloudflare Workers for automation. For broader operations, Kulpinski uses N8N for workflow automation, Typefully for social media scheduling, custom AI content generation, and APIs from Logo.dev and ScreenshotOne for automated favicon and screenshot retrieval.

Growth strategy emphasizes programmatic SEO. Each open-source project receives its own optimized page. Category pages, programming language pages, and "alternatives to X" query pages were created systematically. GitHub data integration—stars, forks, issues, tags—provides automatically updating content that search engines value highly.

Recently, Kulpinski hired a freelance writer for targeted blog content around specific keywords. Automation maintains social media visibility without significant time investment through RSS feed integration with N8N posting across platforms.

Kulpinski runs his entire operation in 2-3 hours weekly through aggressive automation. He identifies three game-changers: automation-first thinking from inception, consistency as competitive advantage in a world where AI enables rapid cloning, and building transparently within the indie hacker community.

Key lessons include starting simple without overthinking, shipping quickly to test traction, delaying monetization to establish trust, automating repetitive tasks, launching everything built regardless of confidence level, and maintaining daily consistency as the ultimate moat.

Looking ahead, Kulpinski aims to build a SaaS generating at least $10,000 monthly recurring revenue. He recognizes dependency on Google rankings as a vulnerability and seeks more defensible distribution through word-of-mouth, network effects, or alternative models. The goal reflects his broader vision: achieving the freedom he sought when leaving employment years ago.

**Revenue Numbers:**
- Total: $13,000/month
- OpenAlternative: $6,500/month (ads/sponsorships 65%, featured listings 35%)
- Dirstarter: $5,000/month (one-time purchases)
- Other directories: $250/month
- Affiliate commissions: $500/month

**Key Lessons:**
- Don't rush monetization. Build trust first, especially in communities sensitive to commercial interests.
- Consistency outweighs novelty; daily execution is the only sustainable competitive advantage
- Automation maximizes efficiency; manual tasks consume critical development hours
- Launch quickly with minimal viable products; real feedback beats theoretical planning

**Tech Stack:**
Next.js 15, Astro (initial), PostgreSQL, Airtable (initial), Vercel, Stripe, Cloudflare Workers, N8N, Typefully, Logo.dev, ScreenshotOne, GitHub data integration
