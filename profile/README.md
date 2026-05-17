# VireoAgents

> Purpose-built agentic AI workflows. Each agent is custom-built, domain-specific, and designed to run autonomously in production. These aren't wrappers around ChatGPT.

**Website**: [vireoagents.com](https://vireoagents.com)
**Operating company**: Vireo LLC

---

## Agent portfolio

| Agent | Status | What it does |
|---|---|---|
| **AgentApply** | Live | Autonomous job search — scores, tailors, and prepares applications across 14+ platforms |
| **AgentScraper** | Live | Fleet-managed data collection with proxy rotation, CAPTCHA solving, distributed workers |
| **AgentMatch** | Deploying | Intelligent two-sided matching — compatibility scoring, plain-language reasoning, feedback learning |
| **AgentProcure** | Planned | Procurement automation — vendor matching, RFP analysis, compliance |
| **AgentInvoice** | Planned | Invoice processing — extraction, validation, routing, exception handling |
| **AgentVerify** | Planned | Identity & credential verification — KYC, biometric auth, background checks, visa/license validation |
| **AgentExtract** | Planned | Document intelligence — multimodal PDF extraction, LLM-powered ingestion of text/graphs/charts/tables at scale |
| **AgentAssist** | Planned | Custom AI assistants — natural language interfaces, tailored templates for focused customer segments |

Naming convention: `Agent[Verb]`. The shared engine behind matching/scoring is **AgentMatch** — extracted from AgentApply's core, packaged for re-use across deployments.

---

## For our team

Internal-only docs live in [`vireoagents/seed-framework`](https://github.com/vireoagents/seed-framework) (private):

- [`FRAMEWORK-PLAN.md`](https://github.com/vireoagents/seed-framework/blob/main/FRAMEWORK-PLAN.md) — source-of-truth design
- [`docs/GETTING-STARTED.md`](https://github.com/vireoagents/seed-framework/blob/main/docs/GETTING-STARTED.md) — scaffold a new agent in one command
- [`docs/ONBOARDING.md`](https://github.com/vireoagents/seed-framework/blob/main/docs/ONBOARDING.md) — new dev setup from `gh auth login` to first PR
- [`docs/GUARDRAILS.md`](https://github.com/vireoagents/seed-framework/blob/main/docs/GUARDRAILS.md) — the Tier-1 rules every project inherits
- [`docs/SECRETS.md`](https://github.com/vireoagents/seed-framework/blob/main/docs/SECRATS.md) — 1Password + AWS SSM model
- [`docs/INFRA-CONVENTIONS.md`](https://github.com/vireoagents/seed-framework/blob/main/docs/INFRA-CONVENTIONS.md) — systemd / nginx / IAM standard shapes

For new machines: `bash <(curl -fsSL https://raw.githubusercontent.com/vireoagents/bootstrap/main/bootstrap.sh)`

---

## For client engagements

VireoAgents (Vireo LLC) takes on custom build engagements. Contact: `connect@vireoconsult.com`.

Standard package pricing for AgentMatch deployments — see internal proposal templates.
