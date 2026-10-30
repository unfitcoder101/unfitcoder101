# Harshvardhan Kasliwal

<img src="https://img.shields.io/badge/OSS-6%20merged%20%C2%B7%2010%20in%20review-2ea44f?style=for-the-badge" />
<img src="https://img.shields.io/badge/DSA-350%2B%20solved-orange?style=for-the-badge" />
<img src="https://img.shields.io/badge/MCA-NIT%20Jamshedpur-blue?style=for-the-badge" />

6 merged PRs across LLMOps and agent-framework codebases, including Agenta (YC) and Mastra (97k★+ combined across the repos below). I verify root cause before touching code, and ship fixes maintainers don't have to rewrite.

🔨 **Right now:** Redis streams worker fix in Agenta that stops a hang on a silent connection ([#7587](https://github.com/Agenta-AI/agenta/pull/7587), in review), plus open LiteLLM router and provider fixes.

---

## Open Source

| Repo | Scale | What I actually fixed |
|---|---|---|
| **LiteLLM** (LLM Gateway) | 62.1k★ | *In review:* audited 28 Databricks model configs, found 26 silently missing schema validation, and fixed it provider-wide instead of patching one model. Also in review: Bedrock tool-call IDs breaking multi-turn conversations, Router discarding provider backoff signals, a budget-bypass bug in spend tracking, and 2 CVE patches. |
| **Mastra** (Agent Framework) | 29.1k★ | *Merged:* removed leaked sub-agent reporting instructions from BUILD/Explore mode prompts ([#24862](https://github.com/mastra-ai/mastra/pull/24862)); fixed dictation transcripts being dropped on normal stop in the React client ([#20016](https://github.com/mastra-ai/mastra/pull/20016)). |
| **Agenta** (LLMOps, YC) | 4.9k★ | *Merged:* JSON Diff evaluator silently ignoring `case_insensitive_keys` for any key with uppercase characters ([#7161](https://github.com/Agenta-AI/agenta/pull/7161)); trace output column now shows the exception message when outputs is null ([#4747](https://github.com/Agenta-AI/agenta/pull/4747)); correct breadcrumb label for SDK evals ([#4619](https://github.com/Agenta-AI/agenta/pull/4619)). *In review:* Redis streams worker that hung forever on a silent connection, timeout and health check added ([#7587](https://github.com/Agenta-AI/agenta/pull/7587)). Also built a RAG chatbot example (LangChain LCEL + vector retrieval + Agenta tracing), live at agenta-ai-examples.vercel.app. |
| **TraceRoot** (Observability) | 1k★ | *Merged:* improved how errors are displayed when testing a bring-your-own-key connection ([#1426](https://github.com/traceroot-ai/traceroot/pull/1426)). |

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
**Languages:** Python · TypeScript · JavaScript · SQL
**Backend:** FastAPI · Node.js · Express · asyncio · REST APIs · JWT
**Data & infra:** MongoDB · PostgreSQL · Redis (Streams) · Docker
**AI / ML:** LangChain · LiteLLM · XGBoost · scikit-learn · SHAP · Groq (Llama)
**Testing & tooling:** pytest · Vitest · Git/GitHub Actions · uv · pnpm
**Frontend:** React

---

## Contact
[LinkedIn](https://linkedin.com/in/harshvardhan-kasliwal-675207229) ·
[X](https://x.com/unfitcoder) ·
[GitHub](https://github.com/unfitcoder101)

📩 Open to remote backend / AI infra roles.
