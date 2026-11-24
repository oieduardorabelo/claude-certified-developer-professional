# Claude Certified Developer – Professional (CCDV-P) — Official Study Sources

All files in `000-sources/` are **primary, authoritative sources** collected directly from Anthropic (Partner Academy Exam Guides, Claude Developer Platform Docs, Claude Code & Agent SDK Docs, Anthropic Engineering Blog), the Model Context Protocol (MCP) official specification, and the external security standards explicitly referenced in the CCDV-P blueprint (OWASP Top 10 for LLM Applications & NIST AI RMF / Generative AI Profile).

## Exam Overview (from the Official Exam Guide v1.0, Nov 2026)

| Attribute | Value |
| :--- | :--- |
| **Credential** | Claude Certified Developer – Professional |
| **Exam Code** | `CCDV-P` |
| **Questions** | 70 scenario-based items (60 scored, 10 unscored) |
| **Time Limit** | 120 minutes |
| **Passing Score** | 720 / 1000 (scaled, criterion-referenced) |
| **Fee / Validity** | $175 USD · Valid 12 months |
| **Assumed Scope** | Claude Certified Developer – Foundations (`CCDV-F`) |

## Directory Map by Exam Domain

| Folder | Exam Domain / Source Type | Weight | Files |
| :--- | :--- | :---: | :---: |
| [`01-exam-guides/`](./01-exam-guides/) | Official CCDV-P Exam Guide, CCDV-F Exam Guide (assumed scope), & Exam Policy PDFs | — | 3 |
| [`02-domain-1-agent-architecture/`](./02-domain-1-agent-architecture/) | **Domain 1:** Advanced Agent Architecture and Orchestration (multi-agent, durable execution, compaction, memory, Agent SDK, Managed Agents) | **17%** | 32 |
| [`03-domain-2-production-integration-grounding/`](./03-domain-2-production-integration-grounding/) | **Domain 2:** Production Integration, Reliability, and Knowledge Grounding (stop reasons, fallbacks, rate limits, batches, cloud platforms, MCP, citations/RAG) | **20%** | 29 |
| [`04-domain-3-observability-monitoring/`](./04-domain-3-observability-monitoring/) | **Domain 3:** Observability and Production Monitoring (OpenTelemetry spans/SDK/API, cache diagnostics, Analytics APIs, ZDR) | **12%** | 16 |
| [`05-domain-4-debugging-incident-response/`](./05-domain-4-debugging-incident-response/) | **Domain 4:** Advanced Debugging and Incident Response (tool-use/thinking/MCP/Agent SDK troubleshooting, prefix checks, error references) | **10%** | 12 |
| [`06-domain-5-evaluation-engineering/`](./06-domain-5-evaluation-engineering/) | **Domain 5:** Evaluation Engineering and Quality Assurance (evals, hallucination reduction, output consistency, plugin evals) | **12%** | 4 |
| [`07-domain-6-cost-latency-optimization/`](./07-domain-6-cost-latency-optimization/) | **Domain 6:** Cost and Latency Optimization at Scale (model routing, prompt caching, streaming, parallel tools, effort levels, budgets, spend limits) | **8%** | 23 |
| [`08-domain-7-guardrails-security/`](./08-domain-7-guardrails-security/) | **Domain 7:** Runtime Guardrails and Production Security (jailbreak/prompt-leak defense, inference hooks, sandboxing, WIF, vaults, MCP OAuth/security) | **11%** | 25 |
| [`09-domain-8-agent-fleet-operations/`](./09-domain-8-agent-fleet-operations/) | **Domain 8:** Agent Fleet Operations for Software Delivery (parallel worktrees, agent teams, dynamic workflows, AI code review, headless/CI, gateways, managed settings) | **10%** | 27 |
| [`10-anthropic-engineering-blog/`](./10-anthropic-engineering-blog/) | Official Anthropic Engineering deep dives (effective agents, context engineering, evals, multi-agent research, MCP code execution, writing tools) | Cross-domain | 7 |
| [`11-standards-owasp-nist/`](./11-standards-owasp-nist/) | External security frameworks explicitly cited in Domain 7 (OWASP Top 10 for LLM Applications 2025, NIST AI RMF 1.0, NIST AI 600-1 Generative AI Profile) | Domain 7 | 3 |

## Recommended Starting Order

1. Read [`01-exam-guides/Claude_Certified_Developer-Professional_Exam_Guide.pdf`](./01-exam-guides/Claude_Certified_Developer-Professional_Exam_Guide.pdf) in full (including the 3 official sample questions and rationales on pages 9–11).
2. Review [`01-exam-guides/Claude_Certified_Developer-Foundations_Exam_Guide.pdf`](./01-exam-guides/Claude_Certified_Developer-Foundations_Exam_Guide.pdf) to verify you have no gaps in the assumed Foundations scope.
3. Study by highest exam weight first: **Domain 2 (20%) → Domain 1 (17%) → Domains 3 & 5 (12% each) → Domain 7 (11%) → Domains 4 & 8 (10% each) → Domain 6 (8%)**, pairing each domain with the corresponding deep dives in `10-anthropic-engineering-blog/` and `11-standards-owasp-nist/`.
