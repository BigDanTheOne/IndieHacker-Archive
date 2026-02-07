# From game development and bug bounties to a $40M/yr product

**Author:** James Fleischmann
**Date:** July 23, 2025
**Source:** https://www.indiehackers.com/post/fC3IxR2MOffWkBSUZqF4

---

George Deglin grew up in the Bay Area surrounded by technology. After majoring in computer science, he cofounded Uversity during his sophomore year. The company built social networking products for universities, raised venture capital, and was eventually acquired.

Later, Deglin met Long, a former Gaia Online founder. Together they launched Hiptic Games, a mobile gaming studio. While running Hiptic Games, both founders faced a critical challenge: retaining players after download. Push notifications existed but lacked reliable infrastructure. They built internal tools for push, email, and SMS messaging—then recognized this wasn't a niche problem and transformed these tools into OneSignal.

During OneSignal's early stage, Deglin supported himself through bug bounties on Facebook, Dropbox, and Coinbase, reaching #2 on Facebook's leaderboard.

OneSignal's MVP was unusually comprehensive. Rather than launching minimal, Deglin and Long built infrastructure supporting push, email, and SMS with mobile SDKs for iOS, Android, and Unity. They prioritized cross-platform support (React Native, Flutter) and localization from day one.

OneSignal's freemium model allows unlimited push notifications, 10,000 free monthly emails, and advanced features on the free tier, creating massive exposure without sales friction.

**Revenue Numbers:**
- Over $40M ARR
- >$3.3M per month
- 2 million+ developers and marketers using the platform
- Powers messaging for one in five apps released worldwide

**Key Lessons:**
- "Scratch your own itch": Building from genuine pain points creates deeper product empathy
- Non-minimal MVPs sometimes succeed: Infrastructure products require substantial initial work
- Freemium drives adoption: Free tier creates massive exposure without sales friction
- Technical prioritization matters: Bug bounty work trained identifying critical paths
- Timing and infrastructure matter: NVMe storage becoming affordable enabled performance promises
- Network effects compound: Word-of-mouth and accessible onboarding create exponential growth

**Tech Stack:**
React, TypeScript, Ruby on Rails (frontend), Rust (core backend services), PostgreSQL, ScyllaDB, NVMe storage
