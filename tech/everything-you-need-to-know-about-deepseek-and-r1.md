# Everything you need to know about DeepSeek and R1

**Author:** Katie Hignett
**Date:** January 28, 2025
**Source:** https://www.indiehackers.com/post/SzPICA1YZ7x4FZmYwIWp

---

DeepSeek, a Chinese AI company founded in 2023 by engineer and hedge-fund founder Liang Wenfeng, has disrupted the AI market with its R1 reasoning model. The company, comprising approximately 140 engineers and researchers, developed R1 for an estimated $6 million -- a fraction of the $100 million to $1 billion spent by U.S. competitors.

## Background on DeepSeek

Liang Wenfeng grew up in Guangdong and studied at Zhejiang University. In 2015, he co-founded High-Flyer Quant, an AI-focused hedge fund that built its own supercomputer. DeepSeek operates as a research-focused venture without commercial profit incentives, with models offered as open source and APIs priced affordably to encourage external development.

## How R1 Achieved Cost Efficiency

Rather than using supervised fine-tuning (SFT), DeepSeek employed reinforcement learning with rule systems and reward mechanisms for accuracy. An early zero-shot version (R1-Zero) spontaneously developed reasoning capabilities. The final R1 combined reinforcement learning with baseline supervised data. Technical limitations from chip embargoes meant reliance on less powerful H800 chips instead of H100s.

## Access for Indie Hackers

- Download distilled, open-source models via HuggingFace (runnable on standard laptops)
- Low-cost API access for integration into applications
- Free chat interface at chat.deepseek.com with usage limits

## Important Considerations

DeepSeek exhibits occasional errors and hallucinations, subject to Chinese government censorship affecting queries about China. User data transfers to Chinese servers, raising privacy and regulatory concerns depending on jurisdiction.

## Key Lessons

1. **Efficiency Over Scale:** Innovative training methodologies can achieve comparable results with significantly lower capital investment.
2. **Open-Source Strategy:** Democratizing access accelerates adoption and external innovation.
3. **Technical Innovation:** Reinforcement learning approaches may offer advantages over traditional supervised fine-tuning.
4. **Market Disruption:** Breakthrough developments can challenge established market assumptions about necessary investment levels.
5. **Data Privacy Considerations:** Users must evaluate geopolitical and regulatory implications of infrastructure location.

## Tech Stack Mentioned

- Models: DeepSeek R1, R1-Zero, distilled versions based on Meta's Llama and Alibaba's Qwen
- Hardware: H800 chips (limited by embargo on H100s)
- Infrastructure: Open-source via HuggingFace platform
- Deployment: API-based and local execution capabilities
