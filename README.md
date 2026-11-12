# Nayan Hazra

Security leader. I work where AI systems meet real infrastructure, and where risk has to be explained to a board as clearly as it is fixed in code.

The repositories below are an assessment kit, the governance framework it reports against, the tools it runs, and a guide for people building a career in the field. Each one began as a question I wanted answered with evidence rather than opinion.

## Selected work

| Project | What it answers | Stack |
|---|---|---|
| [**AI Security Assessment**](https://github.com/thenayanhazra/ai-security-assessment) | Is this AI agent platform safe to run, and what should we fix first? One command runs the four tools below against infrastructure, instruction files, tool servers and the model, and produces a single executive report with a rating, top risks and the governance controls affected. | Python |
| [**AI Security Governance**](https://github.com/thenayanhazra/ai-security-governance) | How should an organisation govern AI that takes actions, and how does a board know it is working? A risk framework, 34 controls mapped to NIST AI RMF, ISO 42001, the EU AI Act, OWASP and MITRE ATLAS, a board reporting pack and a supply-chain policy for MCP servers. | Framework · Policy |
| [**AI Threat Modelling Engine**](https://github.com/thenayanhazra/ai-threat-modelling-engine) | What can go wrong in this architecture, and what should we fix first? Turns diagrams and infrastructure-as-code into STRIDE findings, attack paths, MITRE ATT&CK mappings and an executive PDF. | Python · FastAPI |
| [**MCP Adversarial Harness**](https://github.com/thenayanhazra/mcp-adversarial-harness) | Can a tool server talk an AI agent into acting against its user? Probes MCP servers for prompt injection, tool poisoning and confused-deputy attacks, with SARIF output. | Python |
| [**agentlint**](https://github.com/thenayanhazra/agentlint) | Is the instruction file your agent just loaded safe to trust? A static analyser for SKILL.md, AGENTS.md, IDE rules and MCP configs that catches hidden Unicode, override attempts and exfiltration patterns. | Rust · GitHub Action |
| [**LLM Prompt Injection Fuzzer**](https://github.com/thenayanhazra/llm-prompt-injection-fuzzer) | How often does this model follow an attacker instead of its instructions? Runs 42 injection techniques across six categories and reports bypass rates per category. | Python |
| [**Security Career Paths**](https://github.com/thenayanhazra/security-career-paths) | Where should someone start in security, and how do they grow? Sixteen paths across defence, offence, engineering, governance and AI security, with entry routes, progression, certifications and free resources for beginners and intermediates. | Guide |

## What I focus on

- **AI and agent security.** Prompt injection, tool and supply-chain trust, and the guardrails that hold up in production.
- **Threat modelling at the speed of delivery.** Findings tied to evidence, ranked by consequence, and written so engineers and executives read the same page.
- **Security architecture and governance.** Turning frameworks into decisions people can act on.

## Credentials

CISM · CDPSE · TOGAF · API Security Architect · ITIL · PRINCE2 · Certified Scrum Master · Six Sigma Green Belt

## Elsewhere

[thenayanhazra.com](https://thenayanhazra.com) · [X / @thenayanhazra](https://x.com/thenayanhazra)
