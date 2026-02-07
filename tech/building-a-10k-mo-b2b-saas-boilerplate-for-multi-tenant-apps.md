# Building a $10k/mo B2B SaaS boilerplate for multi-tenant apps

**Author:** James Fleischmann
**Date:** September 17, 2025
**Source:** https://www.indiehackers.com/post/8QiT7aO4qYfwwbL5fvQJ

---

Alexandro Martinez Garcia, a full-stack founder based in Guadalajara, Mexico, discusses how he built SaaSRock, a React Router B2B SaaS boilerplate. His inspiration came from observing his father's flexibility as a software developer.

Martinez began his career 12 years ago migrating his father's ERP system from older technology to modern stacks. This enterprise experience taught him about building complex modules including invoicing, accounting, and inventory management.

**The Product:** SaaSRock helps developers build multi-tenant applications by providing pre-built solutions for user management, granular permissions, admin/account dashboards, subscription billing (recurring, one-time, usage-based), and production-ready SaaS infrastructure.

**Business Model:** SaaSRock operates on a hybrid approach combining product licensing with custom services:
- MVP edition: $249
- Core edition: $499
- Pro edition: $1,999
- Custom development (MVP-as-a-Service): $6,000 to $48,000

**Development Methodology:** Martinez employs spec-driven development combined with Claude Code. His workflow involves documenting project structure through markdown files, requesting Claude to plan features and create PRDs, testing implementations, and maintaining documentation with progress checkmarks.

**Revenue Numbers:**
- $10,000+ per month average for 3.5 years
- 1,500+ users of the boilerplate
- Custom development clients typically $10,000-$16,000 monthly
- 30,000 monthly Google Search impressions

**Key Lessons:**
- Success requires extended effort and patience; the indie hacker dream rarely delivers instant results
- "Keep failing until something sticks"
- Avoid over-engineering and unnecessary abstractions; favor rapid MVP development
- Short video updates (Loom) prove more effective than meetings for client feedback
- Monitor the gap between expectations and results to prevent burnout
- Maintaining diverse revenue streams provides financial flexibility
- Learning to release dead projects is an underrated skill

**Tech Stack:**
React Router v7 (Remix), Tailwind CSS, shadcn/ui, Prisma ORM, PostgreSQL/SQL Server/SQLite, Fly.io/Vercel/DigitalOcean, Cursor IDE, Claude Code CLI
