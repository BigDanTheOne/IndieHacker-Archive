# Vibe coding for newbies - 11 tips for building with AI

**Author:** Channing Allen
**Date:** March 13, 2025
**Source:** https://www.indiehackers.com/post/HlxaY8YDHlI3SaDiEeY0

---

The article presents 11 practical recommendations for developers learning AI-assisted coding techniques. Channing Allen notes that "vibe coding" was coined by Andrej Karpathy just weeks prior.

## The 11 Tips

1. **Smarter models for planning** -- Use advanced AI (Grok 3, GPT-4.5, or o1 Pro) to create product requirements documents before delegating coding tasks to Claude or Cursor.

2. **Restart frequently** -- Embrace iterative development by accepting AI suggestions, reaching breaking points quickly, then rebuilding with accumulated knowledge.

3. **Use separate files** -- Request modular code organization to prevent overwhelming the model's context window and maintain processing efficiency.

4. **Manage context strategically** -- Understanding what information exists in the conversation history is fundamental, as the AI only knows what's presented contextually.

5. **Expect hundreds of prompts** -- Building production-quality applications requires dozens to hundreds of iterative AI interactions, not single-shot solutions.

6. **Write some code yourself** -- Acknowledge that AI will eventually reach limitations, requiring manual debugging and fixes when the model cannot resolve issues.

7. **Use smarter models for review** -- Employ more capable models (Grok 3, o1 Pro) for code review rather than reading all generated code manually.

8. **CRUD apps outperform games** -- Basic database applications are significantly more reliable than graphically demanding projects, as LLMs struggle with vector graphics and visual aesthetics.

9. **Three.js for 3D games** -- When building three-dimensional games, specify this established library as the standard for quality output.

10. **Avoid 2D game engines** -- For two-dimensional games, request custom implementations rather than using established engines, as AI models hallucinate their APIs.

11. **Share your progress publicly** -- Post incremental updates across social media to crowdsource solutions and gain community insights on challenges encountered.

## Key Lessons

- **Context management is crucial** -- Simon Willison's perspective emphasizes that "the craft of getting good results out of an LLM comes down to managing its context."
- **Iterative rebuilding trumps perfection** -- Rather than debugging endlessly, restart projects with newfound understanding.
- **AI has domain-specific strengths** -- CRUD applications represent the practical sweet spot where AI excels; graphical work remains challenging.
- **Manual intervention unavoidable** -- Non-technical developers should expect friction points requiring human coding expertise.
- **Collaborative learning accelerates progress** -- Public building generates feedback loops that enhance solution discovery.

## Tech Stack

- **Code generation models:** Claude Sonnet 3.7, GPT-4.5, Grok 3, o1 Pro Mode
- **Development tools:** Cursor, Windsurf, Claude Projects, VS Code Copilot
- **Frontend frameworks:** Three.js (3D graphics)
