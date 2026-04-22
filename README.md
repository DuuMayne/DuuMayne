# Security & Compliance Engineering

I build open-source tooling for GRC teams. The tools here come from a career spent on both sides of the audit table — as an assessor, as a security engineer, and as someone who helped build one of the platforms the industry runs on.

[LinkedIn](https://www.linkedin.com/in/adamduman/)

### Background

**Internal Security, Vanta** — Four years on the internal security team, working closely with Product to build the Vanta compliance platform. Saw firsthand how a best-in-class GRC tool is designed, what customers actually need, and where the gaps still are.

**Sr Security Engineer** — Built a Security Operations Center from the ground up for a midsize enterprise. Infrastructure, detection engineering, incident response, the full build.

**PCI-QSA, Verizon** — Assessor side, performing PCI DSS assessments. Learned what auditors actually look for and how evidence is evaluated — not just what the standard says, but what makes the difference between a clean assessment and a painful one.

**Security Analyst, AEG** — Hands-on generalist security work at one of the largest live events and entertainment companies in the world. Operational security across a complex, distributed environment.

**AI Governance** — One of the first 200 IAPP AI Governance Professional (AIGP) certified practitioners globally. Hands-on experience implementing ISO 42001 and standing up AI governance programs. The intersection of security, compliance, and AI isn't theoretical for me — I've built the programs and I build with the tools.

### What I'm Building

These tools exist because I've spent years doing compliance work and know which parts are still unnecessarily manual. They're not trying to replace commercial platforms — they're practitioner-built solutions for teams that need something now, can't afford enterprise tooling yet, or want a reference implementation to learn from.

Everything here is AI-assisted development. I design, spec, and direct the builds using [Claude Code](https://claude.ai/code). The domain knowledge is mine. The implementation is accelerated with AI. This is what GRC engineering looks like when practitioners can ship their own tooling.

---

**[RETINA](https://github.com/DuuMayne/RETINA)** — Review of Entitlements, Tokens, Identities and Networked Access

Self-hosted access review tool with 51 SaaS connectors. Pulls user entitlements from across your stack, normalizes them into a consistent schema, and cross-references against your identity provider to flag orphaned accounts, stale access, inactive users, and missing MFA. Built because quarterly access reviews in spreadsheets shouldn't still be a thing.

`Python` `FastAPI` `SQLAlchemy` `SQLite`

---

**[PANOPTICON](https://github.com/DuuMayne/PANOPTICON)** — Proof > Posture

Continuous security control monitoring. Evaluates critical controls across Okta, GitHub, and AWS on a schedule, producing deterministic pass/fail results with evidence snapshots and Slack alerts on drift. When an auditor asks "was this control in place all quarter?", the answer is a time-series — not a screenshot from last Tuesday.

`Python` `FastAPI` `PostgreSQL` `Next.js` `Docker`

---

**[PRISM](https://github.com/DuuMayne/PRISM)** — Predictive Risk Intelligence and Scoring Model

Quantitative risk management with Monte Carlo simulation. Replaces 5x5 risk matrices with actual loss distributions, treatment comparison modeling, and decision-ready framing for leadership. Guided quantification means you answer plain-language questions — the math runs behind the scenes. 25 pre-built scenario templates from real-world risk patterns.

`Next.js` `TypeScript` `SQLite` `Recharts`

---

**[REMEDY](https://github.com/DuuMayne/REMEDY)** — Remediation Tracking

Opinionated workflow for tracking remediation of security findings. Constrained status transitions, mandatory evidence before resolution, immutable audit history, SLA tracking tied to severity. Not a generic ticketing system — built specifically for what auditors expect to see when they review your remediation process. *Currently on hold — integrating directly into PRISM.*

`Next.js` `TypeScript` `Prisma` `SQLite`

---

### Philosophy

The compliance industry has a tooling gap. Enterprise platforms are excellent but expensive. Open-source options are sparse. The teams that need help most — early-stage companies building their first compliance program — often end up doing everything in spreadsheets because that's what they can afford.

I've been fortunate to work at the intersection of security operations, compliance assessment, and product development. These tools are my way of giving back what I've learned. Use them, fork them, learn from them, or just steal the ideas for your own internal tooling.

All projects are licensed under Apache 2.0 with Commons Clause.
