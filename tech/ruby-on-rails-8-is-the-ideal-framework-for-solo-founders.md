# Ruby on Rails 8 is the ideal framework for solo founders

**Author:** Darko Gjorgjievski
**Date:** October 4, 2024
**Source:** https://www.indiehackers.com/post/fZ7ZfstiltJXWGf6ghwu

---

The article argues that Rails 8 represents the ideal web framework for solo entrepreneurs due to its focus on simplicity and reduced complexity.

## Current Web Development Problem

Modern web development has become unnecessarily complicated. The author references collective frustration on forums like Hacker News about React, Vue, front-end tooling, and excessive boilerplate code. Previously, individual developers could mentally "fit" entire web applications in their heads; today's complexity exhausts cognitive capacity.

## The "Brain Budget" Concept

DHH's vision aligns coding simplicity with human cognitive limitations. The goal is compressing modern development complexity into understandable units that fit within mental constraints.

## Key Rails 8 Features

1. **Multi-App Deployment:** Simplified running of multiple Rails applications on single servers with automated SSL configuration via Thruster, Kamal 2, and default Rails 8 features. A single VPS (such as Hetzner's affordable plans) becomes viable.

2. **SSD-Based Systems Replace RAM:** Rails 8 replaces RAM-dependent systems (Redis) with SSD-backed alternatives:
   - **Solid Cable:** WebSocket communications at 50% of RAM-database performance
   - **Solid Cache:** Cache storage
   - **Solid Queue:** Background jobs; Hey.com processes 20 million daily jobs using this

3. **Built-In Authentication:** Eliminates dependency on third-party libraries like Devise.

4. **Integrated Web Server:** Thruster removes Nginx requirements.

5. **80/20 Principle:** DHH claims a "compression factor of 6," allowing faster deployment. Active Record Search provides simplified full-text search for typical use cases.

## Key Lessons

- Modern web development complexity unnecessarily burdens solo developers
- Human cognitive capacity should determine architectural simplicity
- Cost efficiency matters when launching multiple projects
- 80/20 solutions suffice for most applications
- Scale complexity only after achieving significant revenue

**Tech Stack:** Rails 8, Thruster, Kamal 2, Solid Queue/Cache/Cable, SQLite, Hotwire/Turbo, Hetzner VPS
