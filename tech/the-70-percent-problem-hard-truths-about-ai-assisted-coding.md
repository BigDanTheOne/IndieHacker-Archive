# The 70% problem - Hard truths about AI-assisted coding

**Author:** Addy Osmani (Head of Chrome Developer Experience at Google)
**Date:** December 13, 2024
**Source:** https://www.indiehackers.com/post/l6UW9mPaT2uQjGsTxsZO

---

While AI coding tools significantly boost developer velocity, they haven't meaningfully improved software quality. Experienced engineers leverage AI to accelerate known work, while junior developers struggle with code fragility due to limited judgment in evaluating AI suggestions.

## The "70% Problem"

Developers using AI tools quickly reach 70% completion on projects, hitting diminishing returns on the final 30%. Non-engineers particularly struggle because they lack mental models to debug cascading issues, creating a "whack-a-mole" pattern where fixes introduce new problems.

## The Knowledge Paradox

"AI is like having a very eager junior developer on your team. They can write code quickly, but they need constant supervision and correction. The more you know, the better you can guide them."

**Key Lessons:**

1. **Experience Determines AI Value:** Senior engineers use AI to accelerate existing expertise; juniors attempt to learn through AI, producing "house of cards code"

2. **Critical Gaps Remain:** Edge case handling, security, performance, error messaging, and accessibility typically require human judgment

3. **The Polish Problem:** AI excels at happy-path functionality but misses graceful degradation, error states, and user experience refinement

4. **Effective Patterns Work:** "AI first draft" then manual refactoring; "constant conversation" with focused context; "trust but verify" approaches yield better results

5. **Learning Cannot Be Replaced:** Developers must understand generated code rather than passively accept it

## Future Trajectory

Emerging "agentic" systems (Claude's computer use, Cline's autonomous capabilities) will shift from responsive tools to proactive collaborators. Success requires strong architectural thinking and effective human-AI collaboration frameworks.

**Tech Stack Mentioned:**
- Tools: Bolt, v0, screenshot-to-code AI, Cursor, Cline, Copilot, WindSurf, Claude

**Practical Recommendations:**
- Start with small, isolated tasks
- Maintain modularity and clear interfaces
- Question generated code rigorously
- Preserve engineering standards
- View AI as accelerator, not replacement
