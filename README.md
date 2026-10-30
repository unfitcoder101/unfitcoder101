# Harshvardhan Kasliwal

<img src="https://img.shields.io/badge/OSS-6%20merged%20%C2%B7%2010%20in%20review-2ea44f?style=for-the-badge" />
<img src="https://img.shields.io/badge/DSA-350%2B%20solved-orange?style=for-the-badge" />
<img src="https://img.shields.io/badge/MCA-NIT%20Jamshedpur-blue?style=for-the-badge" />

6 merged PRs across LLMOps and agent-framework codebases, including Agenta (YC) and Mastra (97k★+ combined across the repos below). I verify root cause before touching code, and ship fixes maintainers don't have to rewrite.

🔨 **Right now:** 10 PRs in review. LiteLLM router and proxy work: cooling down deployments on stream-fetch failure ([#42815](https://github.com/BerriAI/litellm/pull/42815)), an opt-in flag to honor `Retry-After` across multiple deployments ([#34408](https://github.com/BerriAI/litellm/pull/34408)), capping upstream error bodies at 64 KB ([#34392](https://github.com/BerriAI/litellm/pull/34392)). Plus a Redis streams worker fix in Agenta ([#7587](https://github.com/Agenta-AI/agenta/pull/7587)).

---

## Open Source

| Repo | Scale | What I actually fixed |
|---|---|---|
| **LiteLLM** (LLM Gateway) | 62.1k★ | *In review (8 PRs):* router cooldown and reporting on `fetch_stream()` failure ([#42815](https://github.com/BerriAI/litellm/pull/42815)); opt-in flag to honor `Retry-After` with multiple deployments, with docs ([#34408](https://github.com/BerriAI/litellm/pull/34408), [litellm-docs#643](https://github.com/BerriAI/litellm-docs/pull/643)); cap on upstream error-response bodies at 64 KB ([#34392](https://github.com/BerriAI/litellm/pull/34392)); tool-schema unpacking budget for Bedrock/Vertex ([#34391](https://github.com/BerriAI/litellm/pull/34391)); end-user spend counter reseeding ([#34298](https://github.com/BerriAI/litellm/pull/34298)); hanging-request alert alias fix ([#34307](https://github.com/BerriAI/litellm/pull/34307)); MCP semantic tool filter format fix ([#32606](https://github.com/BerriAI/litellm/pull/32606)); postcss bump for GHSA-r28c-9q8g-f849 ([#34533](https://github.com/BerriAI/litellm/pull/34533)). |
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
**Languages:** Python · C++ · TypeScript · JavaScript · SQL      

**Backend:** FastAPI · Node.js · Express · asyncio · REST APIs · JWT

**Data & infra:** MongoDB · PostgreSQL · Redis (Streams) · Docker

**AI / ML:** LangChain · LiteLLM · XGBoost · scikit-learn · SHAP · Groq (Llama)

**Testing & tooling:** pytest · Vitest · Ruff · Git · GitHub · uv · pnpm

**Frontend & deployment:** React · Vercel · Netlify

---

## Contact
[LinkedIn](https://linkedin.com/in/harshvardhan-kasliwal-675207229) ·
[X](https://x.com/unfitcoder) ·
[GitHub](https://github.com/unfitcoder101)

📩 Open to remote backend / AI infra roles.
