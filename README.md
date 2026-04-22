# Security & Compliance Engineering

I build security, risk, and compliance systems that scale past the people who created them.

The tools here come from a career spent on both sides of the audit table; as an assessor, as a security engineer, and as someone who helped build one of the platforms the industry runs on. The goal has always been the same: build it so well that it doesn't need you anymore, then go build the next thing.

[LinkedIn](https://www.linkedin.com/in/adamduman/) | CISSP | CCSP | CISA | CDPSE | QSA | AIGP

### Background

**Internal Security, Vanta** — Four years on the internal security team, working closely with Product to build the Vanta compliance platform, implementing and maintaining compliance frameworks, and pushing the boundaries of how GRC can and should operate. Saw firsthand how a best-in-class GRC tool is designed, what customers actually need, and where the gaps still are.

**Sr Security Engineer, American Tire Distributors** — Built a Security Operations Center from the ground up for ATD. Infrastructure, detection engineering, incident response, the full build. Handed it off running.

**PCI-QSA, Verizon** — Assessor/Consultant side, performing PCI DSS assessments and supporting PCI-DSS Implementation for some of the worlds biggest hospitality and oil/gas companies. Learned what auditors actually look for and how evidence is evaluated. Not just what the standard says, but what makes the difference between a clean assessment and a painful one.

**Security Analyst, AEG** — Hands-on generalist security work at one of the largest live events and entertainment companies in the world. Operational security across a complex, distributed environment where the threat model changes with every event.

**AI Governance** — One of the first 200 IAPP AI Governance Professional (AIGP) certified practitioners globally. Hands-on experience implementing ISO 42001 and standing up AI governance programs. The intersection of security, compliance, and AI isn't theoretical for me — I've built the programs and I build with the tools.

**Teaching & Community** — Guest speaker and adjunct instructor at IntelliTec College. Coach with We Hack Health. Member of InfraGard. If I've learned something the hard way, I'd rather share it than watch someone else make the same mistake.

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

**Secure yourself out of a job.** The best security programs are the ones that don't need a hero. If your controls only work because one person is watching, they don't work. Everything I build is designed to run on a schedule, produce evidence automatically, and surface problems without someone having to remember to check. The goal is a system, not a person.

**Automate the boring stuff so you can focus on the hard stuff.** Access reviews, evidence collection, control validation — these are important, but they're not where your judgment adds value. They're data collection problems masquerading as security problems. Automate them ruthlessly so you can spend your time on threat modeling, architecture review, and the decisions that actually require a human.

**Build for the auditor in the room.** Every tool here is designed with the assumption that someone is going to ask "prove it." Not "describe your process" — *prove it.* Timestamps, evidence snapshots, immutable history, deterministic pass/fail. If you can't show it, you didn't do it.

**Don't gatekeep.** The compliance industry has a tooling gap. Enterprise platforms are excellent but expensive. Open-source options are sparse. The teams that need help most — early-stage companies building their first compliance program — often end up doing everything in spreadsheets because that's what they can afford. That shouldn't be the case. If I've solved a problem, the solution should be available.

**Practitioners should be able to ship.** I'm not a software engineer. I'm a security and compliance practitioner who builds tooling. AI-assisted development has changed what's possible for domain experts who understand problems deeply but don't write code full-time. The tools here are proof that the people closest to the problem can be the ones who solve it — you don't have to wait for a vendor to prioritize your use case.

I've been fortunate to work at the intersection of security operations, compliance assessment, and product development. These tools are my way of giving back what I've learned. Use them, fork them, learn from them, or just steal the ideas for your own internal tooling.

All projects are licensed under Apache 2.0 with Commons Clause.

For more on my background, certifications, and experience: [linkedin.com/in/adamduman](https://www.linkedin.com/in/adamduman/)
