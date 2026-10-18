# Graph/database package handoff

Original source files are under `backend/app/` and `backend/tests/`. Extract into the ROOT of the NEW repository checkout.

Branch: `feature/graph-database-integration`.

Perform and record actual work: inspect NetworkX evidence graph building, scoring, relationships, and Neo4j persistence; check Python syntax; after all branches merge, run graph pytest tests, start Neo4j, and check `/health` and saved graph behavior. Record actual results in your PR.

This ZIP alone is intentionally not runnable: backend pipeline modules are supplied in another teammate package. Do not commit real database credentials or `.env`.
