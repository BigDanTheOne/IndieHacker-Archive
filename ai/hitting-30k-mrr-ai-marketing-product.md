# Hitting $30k MRR with an AI marketing product

**Author:** James Fleischmann
**Date:** December 18, 2025
**Source:** https://www.indiehackers.com/post/tech/hitting-30k-mrr-with-an-ai-marketing-product-n59ORJCYjnZC61Q096UL

---

Richard Wang has built Leadmore AI, an AI-powered B2B marketing platform that has surpassed $30,000 in monthly recurring revenue and continues accelerating. He's also developing additional products, including ModelFox AI focused on the GEO space, and a B2C entertainment community platform.

## Building in AI

Wang brings over five years of internet industry experience across engineering and product roles at major technology companies. His entrepreneurial drive led him to independent founding, prioritizing work that feels genuinely meaningful and freely chosen.

He selected the AI space because he believes artificial intelligence will fundamentally reshape assumptions underlying traditional internet and mobile platforms, creating expansive opportunities across new markets.

## Validation Before Building

Wang's development process prioritizes these stages:

**Idea Generation:** Insights emerge from observing real user needs through social media conversations and behavior patterns. Success requires asking: "Where do I possess deeper understanding or stronger industry insight than peers?"

**Demand Validation:** Rather than immediately coding, Wang validates through operations and content first. This means sharing demonstrations on social platforms, observing whether potential users appear, and conducting direct conversations to verify their actual needs match assumptions.

**User Research:** Wang typically engages 50-100 potential customers, though even ten substantive conversations can dramatically clarify the problem space and help prioritize requirements.

**Product Development:** "With vibe coding today, you can often ship a very basic MVP in one or two weeks." The emphasis stays on genuine minimalism — if one feature suffices, avoid building additional ones.

## Business Model

Leadmore AI employs credit-based pricing. Users purchase credits for actions like posting, commenting, or discovering relevant communities. Critically, unused credits remain refundable anytime, creating a user-friendly approach.

Revenue growth follows a straightforward formula: "new users multiplied by the conversion rate multiplied by the retention rate." Wang prioritizes retention above all — strong retention indicates the product delivers sufficient value, while weak retention suggests the product fundamentally lacks necessity.

## Technical Architecture

The system runs entirely on serverless infrastructure:
- **Frontend:** Next.js as full-stack framework
- **API:** Go with Gin for high-performance endpoints
- **Data Storage:** MongoDB for core business data
- **Analytics:** ClickHouse for analytical workloads
- **Background Processing:** Function Compute for task processing

## Fighting Feature Expansion

As products mature, competitive pressure intensifies. Competitors may reach out; many ship extensive feature sets. This tempts founders toward feature parity.

However, small teams — typically one or two people initially — cannot execute numerous features effectively or iterate meaningfully. "Human nature pushes you to want more, but this is exactly when product building requires subtraction, not addition."

Wang reflects: "If I could do it all over again, I would reduce my first MVP from three features down to just one."

## Growth Strategy

Leadmore AI's user acquisition centers on operations and content-driven approaches. The company creates and shares industry knowledge across platforms like Reddit, explaining value propositions through practical expertise. When users express interest, direct conversations follow, potentially leading to private community invitations.

Critically, sustained engagement continues post-conversion. The team maintains ongoing communication understanding user needs, pain points, and product shortcomings. This relationship-building naturally compounds into word-of-mouth growth.

## Three Essential Lessons for Independent Developers

1. **Research First:** Spend substantial time — one to three months — conducting user research before building anything. "Until you truly understand the demand, don't start building. Many indie developers default to building first, but I think that mindset is fundamentally flawed."

2. **Strengthen Operations Skills:** "If operations aren't your strength, find a cofounder who is strong in that area. In today's environment, operational ability can, in many cases, be more important than pure development skills."

3. **Avoid Trend Chasing:** Instead, understand your industry strengths and iterate consistently within them. "What really matters is clearly understanding your own industry strengths and continuing to iterate around them. With sustained focus and accumulation in one direction, you're much more likely to achieve meaningful results."
