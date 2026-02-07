# Security bugs engulf ShipFast, a popular indie hacker's product, in drama

**Author:** Stephen Flanders
**Date:** October 23, 2024
**Source:** https://www.indiehackers.com/post/y2VgBkHu7b91rSCEEUSO

---

Marc Lou's popular boilerplate product ShipFast became the center of controversy when indie hacker Simon publicly identified multiple security vulnerabilities. Simon's initial criticism questioned the value of paid boilerplates, then escalated to exposing specific flaws including inadequate server-side validation, insecure Mailgun webhook configuration, and paywall bypass vulnerabilities.

Marc responded dismissively, subsequently blocking critics. This triggered broader community scrutiny, with others discovering additional security issues like free access bypasses and exposed user data. The incident sparked debate about appropriate bug-reporting etiquette, expected security standards for paid products, and community toxicity.

Prominent figures like Pieter Levels recommended security audits and best practices. Marc eventually acknowledged issues, hired security help, and fixed vulnerabilities. The controversy raised questions about balancing rapid development with security responsibility in boilerplate products.

## Revenue Numbers

- ShipFast pricing: $200

## Key Lessons

- Professional communication matters during crises -- dismissiveness damages reputation
- Paid products carrying security-sensitive code require rigorous testing
- Bug reporting should follow responsible disclosure practices
- "Ship fast" philosophy shouldn't override fundamental security practices
- Community accountability can drive improvement

**Tech Stack:** PHP PDO library, SVG, Mailgun webhooks
