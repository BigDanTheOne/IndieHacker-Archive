# Closing in on $50M with an AI coding agent by building for next year

**Author:** James Fleischmann
**Date:** June 27, 2025
**Source:** https://www.indiehackers.com/post/NEGjS4uzKSYltqvxnlTw

---

Igor Ostrovsky left his position in 2021 to explore large language models, eventually creating Augment Code, an AI platform designed specifically for professional software engineers working with large codebases. Only six months after public launch, it is projected to approach $50M in annual revenue.

Ostrovsky grew up in Slovakia with early exposure to computers (Commodore 64, PMD-85). After studying computer science at UBC and competing in programming competitions, he spent eight years building distributed storage systems at Pure Storage before pivoting to AI exploration.

His epiphany came when GPT-3 demonstrated reasoning capabilities around code. Early experiments showed that context-aware completions could identify functions buried thousands of lines away--a genuine pain point no existing tool addressed.

The initial focus was not on interface polish but on two foundational "Big Rocks": a Context Engine (a real-time indexing system handling multi-branch updates, millisecond latency, and codebases with hundreds of thousands of files) and a Custom Code-Completion Model (trained proprietary models in 2022 before open-source alternatives became viable).

A central thesis animates Augment's approach: AI evolves faster than previous platform shifts. Mobile and cloud evolved over five years; LLMs generate breakthrough waves quarterly. The strategy balances shipping for the current wave while secretly building foundations for the next one, requiring modular retrieval, model abstraction seams, and architectural flexibility.

Rather than complex token-based pricing, Augment offers a 14-day unlimited free trial with no sales call required, self-serve IDE integration (minutes to evaluate on real codebases), and enterprise-grade security including SOC 2 Type II and ISO 42001 alignment. Ostrovsky emphasizes that letting engineers experience the difference firsthand outperforms marketing hype.

The competitive advantage is not flashy AI features but unglamorous infrastructure: full-repo context at interactive latency creates defensibility. When new models inevitably commoditize completion layers, the Context Engine remains difficult to replicate.

**Revenue Numbers:**
- Projected ~$50M ARR
- <$4M per month currently
- Achieved explosive growth within 6 months of public launch

**Key Lessons:**
- "Understand the technology, know the customer, know the market--deeply." Three lenses must align before selecting direction
- "Bet forward." Yesterday's cutting-edge commoditizes within months; plan for where models will exist in a year
- "Look at primary sources." Reading papers, testing model code, and training toy checkpoints beats secondhand summaries
- Ship for the current wave while secretly building foundations for the next one
- Full-repo context at interactive latency creates defensibility that is difficult to replicate

**Tech Stack:**
Go, Python, Rust (backend), Kubernetes with gRPC (architecture), VS Code Extension (TypeScript), JetBrains Plugin, Vim/NeoVim, React, TypeScript, Tailwind CSS, Vite, Bazel (frontend), BigTable (analytics), OpenTelemetry, Prometheus (monitoring)
