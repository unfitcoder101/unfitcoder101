# Harshvardhan Kasliwal

<img src="https://img.shields.io/badge/OSS-4%20merged%20%C2%B7%208%2B%20in%20review-2ea44f?style=for-the-badge" />
<img src="https://img.shields.io/badge/LeetCode-300%2B%20solved-orange?style=for-the-badge" />
<img src="https://img.shields.io/badge/MCA-NIT%20Jamshedpur-blue?style=for-the-badge" />
                                
4 merged PRs across production LLMOps and agent-framework codebases at YC-backed startups and high-traffic open-source projects (27k★+ combined). I verify root cause before touching code, and ship fixes maintainers don't have to rewrite.

🔨 **Right now:** shipping fixes across LiteLLM, Agenta, TraceRoot, and Mastra — router retry logic, schema validation gaps affecting 26+ models, tool-call ID sanitization, a router→provider media-loss bug (independently confirmed by Mastra's own triage bot), and 2 dependency CVEs.

---
                      
## Open Source
                         
| Repo | Scale | What I actually fixed |
|---|---|---|
| **LiteLLM** (LLM Gateway) | 26k★ | Audited 28 Databricks model configs, found 26 silently missing schema validation — fixed provider-wide, not patched one model. Also: Bedrock tool-call IDs breaking multi-turn conversations, Router discarding provider backoff signals, a live budget-bypass bug in spend tracking, 2 CVE patches. |
| **Mastra** (Agent Framework) | 17k★ | Fixed a race condition dropping voice-dictation transcripts on normal stop (merged). Also: a router-adapter bug silently dropping image/media tool-results when routed to newer providers — root cause independently confirmed by the project's own automated triage system, with a fix that includes both adapter-level and full router-dispatch regression tests (in review). |
| **Agenta** (LLMOps, YC) | 4.2k★ | Breadcrumb routing bug + trace exception display fix |
| **TraceRoot** (Observability) | 341★ | Normalized error handling across 8 different API providers — survived 6 rounds of maintainer review before merge |

---

## Projects
**Synthetic Oracle** — ML stock signal engine
XGBoost + RF + 4 more models, 74% accuracy, 542 NSE stocks,
13-layer decision engine, SHAP explainability, Groq LLM analysis.
[Live](https://stock-advisor-here.netlify.app) · [Code](https://github.com/unfitcoder101/ai-stock-analyzer-clean)
                     
**CodeArena** — Docker-sandboxed coding platform
Judge0 execution, real-time submissions, AI code review via Groq/Llama.
[Live](https://codearena-frontend-lovat.vercel.app) · [Code](https://github.com/unfitcoder101/codearena-backend)
                   
**StartupOS** — Ops automation dashboard
GitHub API + Google Sheets + Slack webhooks,
rule-based alert engine, multi-tenant JWT auth.
[Live](https://startupos-beta.vercel.app) · [Code](https://github.com/unfitcoder101/startupos)

---

## Stack
Node.js · Express · MongoDB · React · Python · FastAPI ·
Docker · TypeScript · REST APIs · JWT · XGBoost

---                                 
                                                
## Contact                           
[LinkedIn](https://linkedin.com/in/harshvardhan-kasliwal-675207229) ·
[Twitter](https://x.com/unfitcoder) ·
[GitHub](https://github.com/unfitcoder101)
                                     
📩 Open to remote backend / AI infra roles.
