# AI/backend package handoff

Original source files are under `backend/app/`, `backend/tests/`, and `backend/evaluation/`. Extract into the ROOT of the NEW repository checkout.

Branch: `feature/ai-backend-integration`.

Perform and record actual work: inspect claim extraction, Tavily evidence retrieval, Groq JSON response handling, and verdict generation; check Python syntax; after graph files are merged, run relevant pytest tests and verify a real claim with the configured keys. Report actual results in your PR.

This ZIP alone is intentionally not runnable: graph modules are supplied in a separate teammate package. Do not commit real API keys or `.env`.
