# Alibaba drops reasoning model to rival OpenAI's o1

**Author:** Katie Hignett
**Date:** November 30, 2024
**Source:** https://www.indiehackers.com/post/YaNwrIY0XXIS9SA7u43Y

---

Chinese tech giant Alibaba released QwQ-32B-Preview, a large language model with reasoning capabilities comparable to OpenAI's o1 family. The model is accessible via Hugging Face with an Apache 2.0 license for commercial use.

This represents the second reasoning model launch in over a week, following DeepSeek's R1-Lite-Preview released November 20. Both Chinese competitors' models demonstrate step-by-step problem-solving designed for complex reasoning tasks.

Benchmark comparisons show Alibaba's QwQ-32B-Preview outperforms o1-preview on mathematics but underperforms on scientific problems and coding. DeepSeek's R1-Lite similarly excels at math while lagging in coding tasks.

Both models face limitations. They process requests slowly due to extended reasoning chains and occasionally misidentify technical questions as political due to Chinese government content restrictions. QwQ-32B can become trapped in reasoning loops and mix languages.

A new FrontierMath benchmark reveals reasoning models struggle with genuinely novel mathematics problems not encountered during training, though human performance on such problems is comparably poor.

**Key Lessons:**
- Chinese AI companies are rapidly advancing reasoning capabilities
- Government content restrictions create unexpected operational constraints
- Current reasoning models excel in specific domains (mathematics) while remaining weak in others (coding)
- Processing speed remains a practical limitation for reasoning-based approaches

**Tech Stack Mentioned:**
- QwQ-32B-Preview (Alibaba Qwen)
- DeepSeek-R1-Lite-Preview
- OpenAI o1-preview and o1-mini
- Hugging Face platform
