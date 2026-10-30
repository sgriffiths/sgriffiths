# Scott Griffiths

Forward deployed AI engineer. I build agent systems, measure whether they work, and get them through enterprise governance.

## What I'm building

- **[Response Engineering](https://github.com/prime-vector/response-engineering)**: a six-agent incident investigation system, open source. Every finding is traced to evidence with a confidence level and a test that could disprove it, production changes are blocked before execution, and an evaluation harness gates every release. I test my own design choices against the obvious default and keep whichever the evidence supports.
- **Agent control plane** (private, in daily use): a self-hosted task board and supervisor that runs coding agents unattended. Each card is claimed under a lease and runs in a locked-down sandbox: no credentials, network limited to an allow-list, and a credential scan before anything is published. Reviews are blind-first, a fast first pass followed by an independent deep pass from a different model family, both on the exact frozen commit. My GitHub approval of that commit is the only way code reaches main; the supervisor never merges. Disagreements go through a rework budget, and an arbiter model rules when the budget runs out.
- **[Open Agent Spec](https://github.com/prime-vector/open-agent-spec)**: co-author and maintainer. A declarative standard for defining agents as code, with typed outputs, sandboxed tools and behavioural contracts validated in CI.
- **[PrimeVector](https://primevector.com.au)**: co-founder. Behavioural contracts and guardrails for AI agents, across any framework.
- **[SolanaStake](https://solanastake.app)** and **[SolanaRWA](https://solanarwa.app)**: solo-built, live in production. Non-custodial staking where transactions are validated and simulated before the wallet signs, and the backend never signs. Next.js, FastAPI, PostgreSQL, plus an Android app on Google Play.

## How I work

I run more than six projects in parallel through that control plane. The task board is exposed to agents over MCP. Claude and Codex build, Grok reviews first, Codex reviews deep, and I approve. A card goes from enrolled to merged and deployed with my approval as the only review step, and every stage is fenced, receipted and safe to re-run after a crash.

## Interested in

Agent evaluation, AI safety and guardrails, reliability engineering, and getting AI past security review and into production.

## Elsewhere

[scott@genai.com.au](mailto:scott@genai.com.au) · [LinkedIn](https://linkedin.com/in/scgriffiths) · [PrimeVector](https://primevector.com.au) · [Genai](https://www.genai.com.au)
