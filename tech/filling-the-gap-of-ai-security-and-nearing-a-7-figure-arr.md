# Filling the gap of AI security and nearing a 7-figure ARR

**Author:** James Fleischmann
**Date:** September 11, 2025
**Source:** https://www.indiehackers.com/post/KjCtlcYl7xAAz4JvdGFZ

---

Oliver Friedrichs, founder of Pangea, has built four security companies throughout his career since the late 1990s. Pangea launched in 2021 to provide developers with security-focused cloud application tools. The company has developed nearly two dozen developer-oriented security services.

As AI adoption accelerated, Friedrichs identified critical gaps around data leakage, prompt injection, and sensitive information disclosure that traditional security tools couldn't address. He drew parallels to early antivirus development: "words are weapons now instead of the bytes that we used to detect with antivirus products."

Pangea pivoted to focus specifically on AI security, offering a unified platform for securing GenAI applications. The platform detects threats across four main protection categories:
- Prompt injection (ranked #1 in OWASP's LLM threat top 10)
- Confidential information and PII detection (over 50 types)
- Malicious content filtering (partnering with CrowdStrike)
- Topic alignment (ensuring organizational intent)

The core innovation involves using fine-tuned generative AI models (~300M parameters) to detect multilingual prompt injection threats across nearly 100 languages, achieving 99.9%+ efficacy claims.

Growth strategies include developer community engagement, security team targeting, educational content (classifying 169 prompt injection methods), and open source contributions like the Prompt Lab testing tool.

**Revenue Numbers:**
- Less than $83K monthly currently
- Expected to cross 7 figures in ARR in 2025
- Strategic backing: Google Ventures and Okta Ventures

**Key Lessons:**
- "Build with scale in mind from day one" despite starting small
- Prioritize developer experience and integration ease
- Understand market maturity timing: AI security becomes critical only at production stage
- Lead with educational content to build trust
- "Security can't be an afterthought with AI"
- Target security teams first; developers follow once risks become visible

**Tech Stack:**
SDKs in Go, Python, JavaScript, Java, C#; AI gateway integrations (Kong, LiteLLM, Portkey); MCP proxy; Kubernetes/Helm deployment; 300M-parameter fine-tuned detection models; OpenTelemetry; SIEM integrations (CrowdStrike, Splunk)
