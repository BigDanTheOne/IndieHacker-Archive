# Security is a useless controls problem

**Author:** Jonathan Price (Director of Security Operations at Grafana Labs)
**Date:** November 23, 2024
**Source:** https://www.indiehackers.com/post/SUpmWuSejtSsBHeGuMVo

---

The piece opens with the famous Tom Leek StackOverflow metaphor about chimpanzees in a cage learning to avoid bananas through water hoses. This illustrates how security controls persist without understanding their original purpose -- like 8-character password limits stemming from outdated DES encryption limitations.

Price argues that approximately half of industry security budgets fund ineffective controls. He contends that truly valuable controls can be explained simply: "Encryption in transit prevents network interception" or "Private S3 buckets prevent data leaks."

**Core thesis:** Useless controls damage the industry because:
- Resources are severely constrained in security
- People have limited willingness to follow security guidance; wasting it on ineffective measures is destructive
- Compliance frameworks perpetuate wasteful requirements across entire industries
- Contractual obligations create recursive requirements affecting subprocessors

Price advises practitioners to demand clear threat models before implementing any control. If security teams cannot articulate the reasoning concisely, the control likely lacks legitimate purpose.

**Key Lessons:**
1. Understand the "why" before implementing security controls
2. Legitimate controls should be explainable in 2-3 sentences
3. Resource waste undermines organizational security posture
4. Challenge controls that rely on vague justifications

**Tech Stack Mentioned:**
- DES encryption
- TLS/cipher suites
- React (XSS prevention)
- AWS S3
