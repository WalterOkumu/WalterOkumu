# Walter Okumu Oriaro

**Integration Architect & Engineering Leader**
Nairobi, Kenya (UTC+3) · [walterokumu.github.io](https://walterokumu.github.io/) · [LinkedIn](https://www.linkedin.com/in/okumu-oriaro/) · okumu.oriaro@gmail.com

---

I design and run the systems that sit between other systems — payment rails, CRMs, ERPs, analytics platforms and directory data — for a multi-country business operating across seven markets.

Currently **Head of Product Development at Yellow Pages Group**, reporting to the CEO and COO, with technical ownership of the group's product platform across Kenya, Cape Verde, Mozambique, São Tomé, Angola, Tanzania and East Timor. I lead a small engineering team, set the architecture and quality standards, and still write and review the code.

Fourteen years in software, the last four spent almost entirely on systems integration: making things that were never designed to talk to each other work together reliably, across borders, in low-bandwidth markets, on infrastructure we run ourselves.

---

## What I work on

**Multi-system integration platform** — A spec-first integration hub fronting more than twelve external systems: a website platform, a listings platform, three Google data APIs, transactional email, object storage, a CRM, an ERP, a reporting service and a legacy Oracle registry. Fastify and Node on the backend, Next.js on the front, PostgreSQL and Redis behind it, with a 16,000-line OpenAPI contract that generates the shared types. Governance is part of the product: scoped API keys, key rotation, feature flags, integration health monitoring and an encrypted-column layer.

**Payment gateway abstraction** — A payments backend where every provider is an adapter behind one interface: capability negotiation, checkout construction, callback handling and refunds. Adding a market is one new file and one line in the registry. Running in production across two countries and three gateways, including a direct M-Pesa Daraja integration and card acquiring with EMV 3DS 2.2.0.

**Governed data access for AI tooling** — A read-only platform gateway exposing four datastores (PostgreSQL, MySQL, Oracle, Redis) to AI agents and internal services, with the read-only guarantee enforced at the SQL-parse layer rather than by convention, and designed to run VPC-internal with no outbound egress.

**Client integration consulting** — Lead intake middleware for a Portugal-based client, delivered with a written decision record, an explicit scope boundary, thirteen architecture decision records, an operational runbook and a downstream CRM push that ships built but configuration-gated, because the client's CRM is mid go-live.

> Most of this work lives in private repositories. I write about the architecture publicly instead — see **[integration-architecture-notes](https://github.com/WalterOkumu/integration-architecture-notes)**.

---

## Selected outcomes

| | |
|---|---|
| **78%** | reduction in deployment errors after introducing a GitHub Actions + Docker CI/CD pipeline |
| **99.8%** | uptime on the core API infrastructure serving all group digital products |
| **7 countries** | technical delivery span, UTC+1 to UTC+9 |
| **20%** | page-load improvement across a seven-country Drupal → Next.js migration, with no service interruption |
| **40%** | improvement in customer satisfaction while leading a 15-person cross-functional function |

---

## How I work

Specification before implementation. Architecture decisions written down and dated, including the ones that turned out wrong. Conventional Commits enforced in CI, protected branches, tag-triggered deploys, automated versioning. Documentation treated as part of the change, not a follow-up. Mobile-first and WCAG 2.1 AA on anything with a UI.

I have an ISO 9001 habit for process, ISO 31000 for risk and ISO 27001 for security hygiene — applied at the scale a small team can actually sustain, not as paperwork.

---

## Stack

**Backend** Node.js · Fastify · Express · PostgreSQL · Redis · Oracle · MySQL · OpenAPI
**Frontend** Next.js · React · TypeScript / JavaScript · Tailwind CSS
**Infrastructure** Docker · GitHub Actions · self-hosted CI runners · PM2 · Apache2 · Linux VPS · MinIO · AWS (EC2, S3, RDS)
**Integration** REST and webhook design · adapter and registry patterns · queue-backed jobs (BullMQ) · payment rails (M-Pesa Daraja, SISP, card/3DS) · CRM and ERP connectors
**AI** Model Context Protocol servers · agent tool registries and memory · pgvector / RAG · LLM routing

---

## Also

Mentoring full-stack developers at [Microverse](https://www.microverse.org/) since 2022 — weekly code review covering architecture decisions and real-world engineering standards. Three mentees have gone on to their first developer roles.

Building [ContentFloa](https://contentfloa.com), an AI content marketing platform for Small & Medium Businesses.

Working toward AWS Solutions Architect – Associate.
