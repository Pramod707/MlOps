# MLOps

A Python starter project with MLflow as a dependency for machine learning experiment tracking. The current entry point prints a greeting.

## Getting started

Use Python 3.13, the version pinned in `.python-version`, and `uv`. Run these commands from the repository root to install the dependencies from `uv.lock` and run the entry point.

```sh
uv sync --locked
uv run python main.py
```

The script prints `Hello from mlops!`. Check the installed MLflow version with `uv run mlflow --version`.

## Project files

| File | Purpose |
| --- | --- |
| `main.py` | Application entry point |
| `pyproject.toml` | Project metadata and dependencies |
| `uv.lock` | Resolved dependency versions |
