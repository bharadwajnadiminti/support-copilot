# Support Copilot: Progress

## Current position
- Setup step 2 of 5 (folder structure) done. Next: API keys.
- 2026-11-19 re-check, waiting on user to:
  1. Add `C:\Program Files\Git\cmd` to PATH (git not found in PowerShell)
  2. `git init` + first commit (repo not initialized)
  3. Create `.venv` + `pip install -r requirements.txt` (no venv yet)
- Docker missing (only needed in Phase 8).
- Session memory lives in CLAUDE.md (committed, auto-loaded).
- GitHub repo: https://github.com/bharadwajnadiminti/support-copilot (private)
- Plan: use Claude Code on the web (claude.ai/code). Pull before work, push after.
- API keys: local `.env` + web environment variables. Never committed.

## Setup steps
- [x] 1. Environment check (Python 3.13 Store build, Git 2.56, identity set)
- [x] 2. Folder structure, .gitignore, requirements.txt
- [ ] 3. API keys in .env (Google AI Studio, Groq)
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
