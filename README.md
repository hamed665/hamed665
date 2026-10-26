# Hamed Minaei
### Full-stack & Applied AI Engineer

**Hamed Minaei** · Python · TypeScript · Business automation

I build practical software around conversational interfaces, document workflows and controlled automation. I focus on clear interfaces, explicit workflows and reproducible tests.

**Working stack:** Python · TypeScript · React / Next.js · FastAPI · PostgreSQL · Docker

[Resume project briefs](RESUME_PROJECTS.md) · [Detailed engineering evidence](PORTFOLIO_STATUS.md)

## Selected engineering work

| Project | My development | Evidence and scope |
| --- | --- | --- |
| [Customer Support Workspace](https://github.com/hamed665/ai-customer-support-saas) | Multilingual inbox, business metrics, source citations and human handoff | 18 engine tests, Next/browser checks and security gate passed. [Try the live synthetic demo](https://hamed665.github.io/ai-customer-support-saas/support-demo/). |
| [Document Intelligence API](https://github.com/hamed665/ai-document-intelligence) | Authenticated extraction, structured invoice fields and bounded batches | 11 tests, real TXT/DOCX conversions and an isolated non-root, read-only Docker execution passed. |
| [Knowledge Retrieval Workbench](https://github.com/hamed665/enterprise-rag-knowledge-base) | Local ingestion, source citations, abstention and evaluation | Build, API and browser tests passed. Extractive retrieval preview; no claim of LLM generation or enterprise readiness. |
| [Voice Agent Runtime](https://github.com/hamed665/realtime-ai-voice-agent) | Configurable interruption behavior, redacted transcripts and consent-controlled export | 11 tests and CI passed. Offline replay available; live audio/provider testing remains pending. |
| [Business Automation Pack](https://github.com/hamed665/self-hosted-ai-automations) | Three n8n workflows for leads, invoices and support triage | Policy tests and actual container execution passed. Synthetic data; optional local-model inference remains unverified. |

## In development

- [Browser Automation Workbench — PR #1](https://github.com/hamed665/ai-browser-automation-agent/pull/1): approval gates, task state, execution logs and protected screenshots. Ten tests, cancellation/replay checks and the real Chromium/HTTP flow pass; legacy dependency security and full model integration remain unresolved.

The integration projects above are open-source integration and extension projects. Each repository identifies its upstream foundation, original license and my additions. I preserve attribution and original commit history.

## Original backend reference projects

Five standalone Python projects with runnable offline demos, synthetic fixtures and **43 passing local tests**. Each includes installation instructions, design notes, limitations and a Python 3.11–3.13 CI workflow. These are library/CLI reference implementations, not hosted production services.

| Project | Engineering focus | Local tests |
| --- | --- | --- |
| [SlotGuard](https://github.com/hamed665/reservation-conflict-engine) | Transactional booking conflicts, UTC normalization and competing requests | 8 |
| [MergeDesk](https://github.com/hamed665/crm-sync-conflict-resolver) | Three-way CRM merge, deletion semantics and explicit conflict review | 9 |
| [TokenLedger](https://github.com/hamed665/llm-budget-ledger) | Exact cost accounting, atomic budget reservations and usage settlement | 9 |
| [CatalogLens](https://github.com/hamed665/catalog-search-workbench) | Explainable BM25 search, business filters, Unicode and offline evaluation | 9 |
| [RelayBox](https://github.com/hamed665/event-outbox-worker) | Atomic outbox writes, fenced leases, retries and dead-letter recovery | 8 |

## Interactive engineering workbenches

Five original JavaScript projects with **40 passing local tests**, an editable browser demo, JSON report export and a Node CLI. Each browser demo is generated from the same engine source used by the tests, and runs offline without an API key. These are reference implementations with synthetic data; production integration boundaries are documented per project.

| Workbench | Engineering focus |
| --- | --- |
| [ChronoJoin](https://github.com/hamed665/point-in-time-feature-lab) | Point-in-time feature joins with event/availability checks and provenance |
| [ContractDesk](https://github.com/hamed665/dataset-contract-workbench) | Strict dataset contracts, duplicate quarantine and value-redacted issue reports |
| [FlagPilot](https://github.com/hamed665/release-rollout-workbench) | Deterministic rollout buckets, stable exposure and a kill switch |
| [SignalWatch](https://github.com/hamed665/streaming-anomaly-workbench) | Event-time replay, watermarks and cumulative online anomaly baselines |
| [GateFlow](https://github.com/hamed665/approval-workflow-replay) | Dependency graphs, explicit approval gates and auditable event replay |

## How I work

- Start with an observable baseline and document limitations.
- Keep demonstrations synthetic and independent of customer or production systems.
- Test behavior, preserve reviewable changes, and publish CI evidence.
- Treat human approval, secret handling and dependency licensing as part of the design.

Explore the repositories and pull requests for implementation details, reproducible test commands and measured results. These are portfolio previews with synthetic data. Live voice/model verification, full backend integration and production hardening remain project-specific follow-up work, documented in each repository.

[Detailed verification report and demo limitations](PORTFOLIO_STATUS.md)
