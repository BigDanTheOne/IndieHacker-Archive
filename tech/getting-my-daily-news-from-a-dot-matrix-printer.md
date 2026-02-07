# Getting my daily news from a dot matrix printer

**Author:** Andrew Schmelyun
**Date:** October 10, 2024
**Source:** https://www.indiehackers.com/post/8BS6kuPDtVOTp1Ku3nom

---

Schmelyun built an automated system that prints personalized daily news to physical paper each morning. The script aggregates weather, stock prices, news headlines, and Reddit posts, then formats them within the printer's 80-character width limitations.

He notes the psychological benefit: "it just feels better having that finite amount of news on a single sheet of paper."

The creator discovered that reducing screen time while maintaining news awareness is achievable through creative hardware integration. He learned that older technology can be repurposed effectively when you understand its specific constraints, such as the printer's character set based on IBM PC Code Page 437. The project demonstrates how free public APIs enable affordable experimentation with unconventional projects.

Source code is available on GitHub (aschmelyun/dotmatrix-daily-news).

## Key Lessons

- Reducing screen time while maintaining news awareness is achievable through creative hardware integration
- Older technology can be repurposed effectively with understanding of specific constraints
- Free public APIs enable affordable experimentation

**Tech Stack:** Star NP-10 dot matrix printer, Raspberry Pi Zero W, Serial to USB adapter, PHP, Open-Meteo API, Twelvedata API, NYTimes API, Reddit JSON, Cron jobs
