# The problem with OpenAI's o1 reasoners

**Author:** Aidan McLaughlin
**Date:** December 6, 2024
**Source:** https://www.indiehackers.com/post/xSZbMwnBb5iCIL2Am6Ur

---

o1 reasoners represent the most significant advancement since the original GPT-4, validating predictions about extended model thinking rather than pure size increases. However, they fundamentally fail on problems that genuinely matter.

## RL Magic Has Limits

Reinforcement learning powered breakthroughs like AlphaZero, but its effectiveness depends on clear, frequent reward signals. Most real-world problems lack such clarity. The author explains: "RL is great for board games, high-frequency trading, protein folding, and sports... but not for open-ended thought."

o1 works by treating reasoning steps as actions within constrained domains -- math, coding, standardized tests -- where verification is straightforward. This creates "sparse reward" problems where RL struggles.

## Transfer Learning Failure

Despite hopes for generalization, o1-style reasoners don't meaningfully transfer beyond their training domains. Evidence includes:

- o1-preview performs *worse* than the 6x cheaper GPT-4o on writing tasks
- DeepSeek's r1 shows identical reasoning patterns to standard models on non-math problems
- On emotional intelligence benchmarks (EQBench), o1-mini matches GPT-3.5-turbo performance

The author notes: "The skills learned in narrow domains *do not* transfer to all domains."

## The Larger Problem

The AI industry appears to have abandoned scaling model size since GPT-4 (March 2023). Simultaneously, resources shifted toward replicating o1 rather than developing larger models. This creates a strategic problem: without bigger models, AI remains at GPT-4 level for domains without easy verification including corporate strategy, creative writing, philosophy, research, social trend analysis, and interpersonal advice.

**Key Lessons:**
1. RL has fundamental limitations for open-ended problems lacking clear feedback mechanisms
2. Narrow specialization doesn't generalize -- reasoning improvements in math/coding don't transfer to broader domains
3. Model size scaling may have stalled
4. Inference compute scaling has limits -- it cannot substitute for actual capability improvements through training
5. Current reasoning models won't solve real-world problems requiring judgment, creativity, or nuanced understanding

**Tech Stack Mentioned:**
- Language Models: GPT-4, GPT-4o, Claude-3.5, o1-preview, o1-mini, DeepSeek r1
- Benchmarks: ARC, EQBench
- Tools: Stockfish (chess engine), OpenRouter
