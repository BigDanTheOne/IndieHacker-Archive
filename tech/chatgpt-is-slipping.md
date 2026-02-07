# ChatGPT is slipping

**Author:** Adriano Caloiaro
**Date:** November 22, 2024
**Source:** https://www.indiehackers.com/post/XvmJxKP6arKkWbGYU2eO

---

Adriano describes deploying a production system using GPT-4o and GPT-4o-mini to analyze business feedback and categorize it. The solution worked reliably for three months, passing rigorous test suites (run 50 times weekly). On November 13, 2024, tests began failing. Initially treating it as typical flakiness, Adriano later discovered the models had fundamentally regressed -- failing all 1,000 test iterations when presented with production-scale data volumes.

The feature spectacularly failed on November 15, producing unusable results for users. Adriano suspects an undisclosed parameter change in GPT-4o affected his use case specifically. By November 18, performance mysteriously restored. He expresses concern that "OpenAI is comfortable taking API users for a ride" without transparency about model changes.

**Key Lessons:**
- LLMs lack established reliability in deterministic contexts
- Third-party AI models can degrade unexpectedly without public notification
- Production scaling reveals model limitations invisible in testing environments
- API stability shouldn't be assumed despite apparent reliability

**Tech Stack Mentioned:**
- GPT-4o, GPT-4o-mini (OpenAI models)
- Langchaingo (provider abstraction)
- Ollama (local-first LLMs)
- Go programming language
