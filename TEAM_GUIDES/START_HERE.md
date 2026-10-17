# TruthGraph Team — start here

This new repository is assembled from a source snapshot of the existing TruthGraph project. Original application files are preserved byte-for-byte. The initial application was developed by the original author; package imports are integration activity, not proof of original authorship by the person pushing them.

## Assembly order

1. Repository owner creates a brand-new EMPTY GitHub repository, initializes `main` from `01-TruthGraph-Base.zip`, and pushes it.
2. Invite all three teammates as collaborators. They accept invitations.
3. Each teammate clones the NEW repository (not the old one), creates a distinct branch from `main`, extracts their assigned ZIP into the repository root, inspects the diff, runs relevant checks, commits their actual integration work, and opens a pull request.
4. Review and merge frontend, AI/backend, and graph/database PRs. The files are partitioned so original source file paths do not overlap.
5. After all three merges, run `shasum -a 256 -c TEAM_GUIDES/source_manifest.sha256` from repository root. All original files should say `OK`.
6. Install dependencies and verify the full website. Do not commit `.env`, keys, `node_modules`, or `.venv`.
7. Record actual tests, reviews, and integration activities in GitHub PR descriptions and the contribution record.

See the separately supplied `TruthGraph-Team-GitHub-Guide.md` for copy/paste commands and troubleshooting.
