# Improving accessibility using vision models

**Author:** Michael Barajas
**Date:** October 10, 2024
**Source:** https://www.indiehackers.com/post/vhI8i4AGHa4JOm1FPwpl

---

The article chronicles Michael Barajas's experience migrating math courses between platforms. He discovered that equations were represented as low-quality images without alt-text, creating accessibility barriers for students. He investigated whether vision models could automatically generate LaTeX representations of these equations.

Barajas tested three AI models (GPT-4o, Gemini 1.5 Pro, and Gemini 1.5 Flash) on 300 equation images, comparing their outputs against a database of correct LaTeX answers. Results showed Gemini 1.5 Flash achieved a 5.24% error rate compared to GPT-4o's 11.49%. He observed that error rates increased with equation complexity, peaking around 30-character equations.

The primary errors in GPT-4o's outputs involved confusing minus symbols with equal signs and misidentifying individual characters. Barajas implemented Gemini 1.5 Flash to convert equations to LaTeX, flagging equations exceeding 20 characters for manual review. This approach reduced manual work significantly, as only 27% of questions contained longer equations.

## Key Lessons

- Vision models can effectively assist with accessibility improvements
- Smaller, efficient models may outperform larger ones for specific tasks
- Hybrid approaches (automated + manual review) optimize resources

**Tech Stack:** GPT-4o (OpenAI), Gemini 1.5 Pro and Flash (Google), Python, SQLite, LaTeX, LMS
