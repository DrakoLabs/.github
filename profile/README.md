# DrakoLabs

**Security and governance infrastructure for the age of AI agents.**

AI agents are moving from prototypes to production. They call tools, spend money, handle sensitive data, and take actions on behalf of your organization — often without a human in the loop. The security posture of most deployments reflects how fast that transition happened.

DrakoLabs builds the infrastructure to govern what agents can do: before you ship, and after you deploy.

---

## Core Project

### [Drako](https://github.com/DrakoLabs/drako) — AI Agent Security & Governance Platform

Static analysis and runtime enforcement for AI agent systems. Scan your codebase before deployment. Enforce policy at the tool call level in production. No cloud dependency required.


**What it does:**

- **Static scanning** — 97 deterministic rules across security, governance, compliance, determinism, and operational boundaries. No LLM in the evaluation loop. Same code, same result, every time.
- **Agent BOM** — Inventory every agent, tool, model, framework, and dependency in your codebase. Pure AST. Fully offline.
- **Runtime enforcement** — A 13-stage policy pipeline on every tool call. DLP, HITL checkpoints, circuit breakers, spend caps, cryptographic audit trail.
- **Proxy mode** — Out-of-process enforcement. Zero code changes. The agent cannot bypass what doesn't run in its process.
- **EU AI Act alignment** — Articles 9, 11, 12, and 14 covered. Audit-ready from day one.

Governance overhead under 0.3% of a typical LLM call. P99 full scan under 4ms.

---

## Principles

**Determinism over inference.** Rules are static and reproducible. No model decides whether your agent is safe.

**Depth over dashboards.** Reachability analysis separates real risk from theoretical exposure. A dangerous tool no agent actually calls is flagged — not treated as critical.

**Offline first.** Scanning requires no account, no network, no vendor dependency. Governance infrastructure should not itself be a single point of failure.

**Lifecycle coverage.** Security posture is established at development time and enforced at runtime. Both layers matter.

---

## Built for What's Coming

The frameworks are maturing. The regulations are arriving. The attack surface is expanding — prompt injection, tool misuse, runaway spend, unaudited actions, cascading multi-agent failures.

Drako is built for teams that are shipping agents to production now and need governance infrastructure that keeps up.

---

[getdrako.com](https://www.getdrako.com) · [github.com/DrakoLabs/drako](https://github.com/DrakoLabs/drako)
