# agent-eval-cicd-pipeline

CI/CD and evaluation pipeline for shipping reliable agent updates.

## Scope

Eval suites, regression gates, and deployment promotion policies.

## Capabilities

- Eval suites, regression gates, and deployment promotion policies.
- Dataset versioning and benchmark lineage for reproducible scoring.
- PR checks integrating quality, safety, and cost thresholds.
- Automated release notes and change-risk classification.

## Repository Layout

- `src/main.py` entrypoint and lightweight service bootstrap
- `src/project_profile.py` canonical project metadata
- `src/service_contract.py` baseline domain contract shape
- `tests/` smoke and contract tests
- `docs/` architecture and roadmap

## Quick Start

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -e .[dev]
pytest -q
python -m src.main
```
