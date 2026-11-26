# Claude Certified Developer – Professional (CCDV-P) Study Hub

Study material for the **Claude Certified Developer – Professional** (`CCDV-P`) exam.

**Live site:** https://oieduardorabelo.github.io/claude-certified-developer-professional/

## What's inside

- **8 domain study guides.** Each one has a voice-over (Kokoro neural voice) with word-by-word highlighting, so you can read and listen at the same time.
- **Exam simulator.** 128 scenario-based questions in a proctored-style mode: countdown timer, flag for review, option strikethrough, question navigator, review before submit, and a scaled score report. The pass mark is 720 / 1000.
- **Source library.** The docs, blog posts, and standards the guides are built from, grouped by exam domain.

## Exam domains

| # | Domain | Weight | Guide |
| :-: | :--- | :-: | :--- |
| 1 | Advanced Agent Architecture and Orchestration | 17% | [`001-agent-architecture`](./001-agent-architecture/) |
| 2 | Production Integration, Reliability, and Knowledge Grounding | 20% | [`002-production-integration-grounding`](./002-production-integration-grounding/) |
| 3 | Observability and Production Monitoring | 12% | [`003-observability-monitoring`](./003-observability-monitoring/) |
| 4 | Advanced Debugging and Incident Response | 10% | [`004-debugging-incident-response`](./004-debugging-incident-response/) |
| 5 | Evaluation Engineering and Quality Assurance | 12% | [`005-evaluation-engineering`](./005-evaluation-engineering/) |
| 6 | Cost and Latency Optimization at Scale | 8% | [`006-cost-latency-optimization`](./006-cost-latency-optimization/) |
| 7 | Runtime Guardrails and Production Security | 11% | [`007-guardrails-security`](./007-guardrails-security/) |
| 8 | Agent Fleet Operations for Software Delivery | 10% | [`008-agent-fleet-operations`](./008-agent-fleet-operations/) |

Exam simulator: [`009-exam-questions`](./009-exam-questions/)

## Repo layout

```
.
├── index.html                  # Study hub home page
├── 001-… to 008-…/             # One folder per domain: index.html + audio.m4a
├── 009-exam-questions/         # Exam simulator (question bank lives inside index.html)
├── 000-sources/                # Source docs by domain (see 000-sources/README.md)
└── 010-quiz-sessions/          # Notes from practice quiz sessions
```

## Run locally

No build step. Everything is plain HTML, CSS, and JavaScript.

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

Opening `index.html` straight from disk also works. A local server is safer for audio playback.

Exam progress and history are saved in your browser's `localStorage`.

## Notes

- This is an unofficial, personal study project. It is not made or endorsed by Anthropic.
- Files in `000-sources/` come from their original authors (Anthropic, the Model Context Protocol project, OWASP, NIST). They are here for study reference only.
- Practice questions are written for study. They are not real exam items.

---

Made with ♥ by [@oieduardorabelo](https://github.com/oieduardorabelo)
