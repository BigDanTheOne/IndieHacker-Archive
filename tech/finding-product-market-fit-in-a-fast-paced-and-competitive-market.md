# Finding product-market fit in a fast-paced and competitive market

**Author:** James Fleischmann
**Date:** December 4, 2024
**Source:** https://www.indiehackers.com/post/EcUFuZ3VNH94SZwMI5Y7

---

Emma Lawler, a second-time founder, discusses building Velvet, an AI gateway platform for model analytics and monitoring. Previously, she grew developer marketplace Moonlight to $10K MRR before its acquisition by Google-backed PullRequest in 2020.

Velvet initially launched as an AI copilot enabling text-to-SQL queries. Through customer usage analysis, the team identified demand for AI-specific infrastructure tools. A key customer request to access gateway functionality directly informed their product pivot toward warehousing and analyzing LLM request logs from OpenAI and Anthropic.

The product launched as self-serve in September after summer development with a design partner customer. Today, hundreds of developers use Velvet across 60+ million logged requests, with the company approaching six-figure annual recurring revenue through mixed bottom-up adoption and enterprise contracts.

## Revenue Numbers
- Previous startup (Moonlight): $10K MRR with $55K monthly GMV
- Velvet: Less than $10K per month (current state)
- Velvet: "approaching six-figures in ARR"
- 60+ million requests logged

## Key Lessons

**Product Development:**
- Build based on customer feedback rather than assumptions
- Ship early and often to maintain momentum
- Pivot toward signals of real demand observed through usage patterns

**Pricing Strategy:**
- Use value-based pricing for software with upfront costs
- Transition from per-request billing to annual plans with usage tiers as customers scale

**Go-to-Market Approach:**
- Employ two-pronged strategy: free self-serve tools plus enterprise annual contracts
- Leverage multiple channels: HackerNews, Product Hunt, LinkedIn outreach, event speaking

**Founder Decisions:**
- Develop products before fundraising when possible
- "Momentum is the only thing that matters when building a 0-1 startup"

## Tech Stack

**Frontend/Application:**
- Next.js
- Node.js

**Database:**
- Neon (per-workspace instances)
- PostgreSQL (customer-controlled option)

**Infrastructure (Current):**
- Cloudflare Workers
- Cloudflare KV
- Cloudflare Queues
- Cloudflare Analytics Engine

**Other Tools:**
- Beehiiv (newsletter platform)
