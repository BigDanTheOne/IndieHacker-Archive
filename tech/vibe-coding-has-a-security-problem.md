# Vibe coding has a security problem

**Author:** Channing Allen
**Date:** March 19, 2025
**Source:** https://www.indiehackers.com/post/vLxyPTrTlZVwDo76oqvr

---

The article examines security vulnerabilities faced by non-technical founders using AI-assisted "vibe coding" to rapidly develop applications. It uses Leo Jr.'s experience as a case study -- a non-technical indie hacker who built EnrichLead publicly but faced significant security threats after gaining visibility.

## Main Issues Discussed

1. **Exposed API Keys:** Leo's codebase contained API keys in publicly accessible locations, allowing unauthorized access to his system's authentication credentials.

2. **Weak Paywalls:** His product featured CSS-based paywalls easily bypassed through browser developer tools, as one critic noted: "your paywall is bypassed by two lines of CSS."

3. **Broader Pattern:** The article references similar incidents affecting other builders -- Marc Lou's ShipFast and Pieter Levels' flight simulator both experienced security exploits after gaining prominence.

## Key Recommendations

- Store API credentials using environment variables rather than hardcoding them
- Implement server-side (backend) paywall enforcement instead of client-side CSS hiding
- Use JavaScript-based obfuscation as a temporary intermediate solution

## Outcome

Leo ultimately shuttered his application, citing continuous code breaks from Cursor and deciding to rebuild using Bubble, a no-code platform marketed as more secure for non-technical creators.

## Key Lessons

- "Shipping fast" without security awareness creates vulnerability to exploitation
- Popular applications and public builders naturally attract malicious attention
- Basic security practices can significantly reduce risk without requiring extensive technical expertise
- Security should be prioritized early, not deferred until problems emerge

## Tech Stack References

- **AI Coding Tool:** Cursor
- **API Management:** Generic APIs requiring authentication keys
- **Alternative Platform:** Bubble (no-code)
- **Infrastructure:** Cloudflare (mentioned for DDoS mitigation)
- **Previous Tools:** GitHub (for code repositories)
