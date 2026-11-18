# Support Copilot: Progress

## Current position
- Setup step 2 of 5 (folder structure) done. Next: API keys.
- 2026-11-19: git repo set up + pushed, `.venv` created, all packages import OK.
- Step 3 done: .env has GOOGLE_API_KEY + GROQ_API_KEY, both verified (HTTP 200).
  Pending: user creates + commits .env.example; adds keys to web env vars.
  NEXT: setup step 4 (dummy data + validation script).
- Models available (2026-11-19): Gemini `gemini-2.5-flash`, `gemini-2.5-flash-lite`,
  embeddings `gemini-embedding-001`. Groq `openai/gpt-oss-20b`, `qwen/qwen3.8-27b`.
- Windows Smart App Control (On) blocked unsigned DLLs in xxhash 4.1, numpy 2.5,
  grpcio 1.85. Fixed by pinning older versions in requirements.txt. If a new
  "DLL load failed ... Application Control policy" error appears, pin an
  older version of that package.
- Docker missing (only needed in Phase 8).
- Session memory lives in CLAUDE.md (committed, auto-loaded).
- GitHub repo: https://github.com/bharadwajnadiminti/support-copilot (private)
- Plan: use Claude Code on the web (claude.ai/code). Pull before work, push after.
- API keys: local `.env` + web environment variables. Never committed.

## Setup steps
- [x] 1. Environment check (Python 3.13 Store build, Git 2.56, identity set)
- [x] 2. Folder structure, .gitignore, requirements.txt
- [x] 3. API keys in .env (Google AI Studio, Groq)
- [ ] 4. Dummy data + validation script
- [ ] 5. Start Phase 1

## Phases
- [ ] 1 Setup + LangGraph basics
- [ ] 2 Prompts + structured output (Pydantic)
- [ ] 3 RAG
- [ ] 4 Tool calling + agent loop
- [ ] 5 FastAPI backend
- [ ] 6 Evals
- [ ] 7 Observability
- [ ] 8 Guardrails, Docker, deployment

## Tasks done
(none yet)

## Concepts I struggled with
(none yet)

## Things to revise
(none yet)
