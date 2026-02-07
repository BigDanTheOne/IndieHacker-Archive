# Why LLMs within software development may be a dead end

**Author:** David Eastman
**Date:** December 6, 2024
**Source:** https://www.indiehackers.com/post/tOyDjy7H68y8xKPcapDN

---

The article critiques using Large Language Models as product components rather than as development tools. David Eastman argues that LLMs lack the decomposability required for sustainable software architecture.

**Core Argument:** Current LLMs cannot function as reliable, testable software components because they lack internal structure that relates to functionality. They resist the modular design principles fundamental to computing.

**Key Problems Identified:**

1. **Lack of Decomposability** - "Current AI systems have no internal structure that relates meaningfully to their functionality. They cannot be developed, or reused, as components."

2. **Inseparability from Training Data** - The operation of an LLM cannot be separated from its training process, which typically remains opaque and non-reproducible.

3. **Security & Privacy Concerns** - Neural networks cannot be meaningfully intercepted to enforce privacy protections or prevent information leakage.

4. **Legal Ownership Issues** - Unlike deterministic systems, LLMs cannot prove they haven't incorporated prior art, creating intellectual property risks.

5. **Environmental Cost** - LLM development requires exponential computing resources for diminishing returns.

**Recommendation:** Developers should advocate for "truly explainable Artificial Intelligence with testable components" where training is monitored, repeatable, and reversible.

**Key Lessons:**
1. LLMs should remain tools for development, not product components
2. Software components require testability, replaceability, and clear separation of concerns
3. Current LLM opacity contradicts fundamental computing principles
4. Business incentives favor keeping LLMs proprietary rather than decomposable
5. True AI innovation requires explainability standards, not faith-based adoption

**Tech Stack Mentioned:**
- Oracle database (architectural comparison)
- Cursor (AI coding tool)
- Zed AI (AI coding tool)
- Zoom (product example)
