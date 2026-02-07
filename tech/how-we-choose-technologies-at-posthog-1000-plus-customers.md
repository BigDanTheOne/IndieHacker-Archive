# How we choose technologies at PostHog (1,000+ customers)

**Author:** Ian Vanagas
**Date:** December 6, 2024
**Source:** https://www.indiehackers.com/post/LyKXL3L72fUI4HtsGRz5

---

## Key Lessons

1. **Prioritize Critical Problems:** Address only "hair-on-fire problems" involving excessive costs, scaling challenges, or customer demands rather than nice-to-have features.

2. **Evaluate Realistically:** Test technologies "as close to the real world as possible" using production-safe testing, proof-of-concepts, and real data rather than theoretical benchmarks.

3. **Balance Technical and Business Factors:** Consider performance, cost, reliability, support quality, and flexibility alongside engineering considerations to enable faster decision-making.

4. **Use Asynchronous Decision Processes:** Implement request-for-comments (RFC) documentation to gather team feedback transparently while empowering implementers to make final calls.

5. **Continuously Reassess:** Maintain ongoing evaluation of adopted technologies to ensure long-term alignment with strategic goals, even for proven solutions.

## Cost Metrics
- EFS evaluation showed $300/month estimate but actual cost reached "$600/day"
- S3 for replay storage helped "make replays drastically cheaper"

## Tech Stack Mentioned
- **Languages/Frameworks:** Python, Rust, C++, Hog (proprietary language)
- **Infrastructure:** AWS, Kafka, ClickHouse, Temporal, Warpstream, Pulsar, PostgreSQL
- **Storage:** S3, ByConity, Apache Iceberg
- **Services:** Cloudflare (referenced as early adopter)
