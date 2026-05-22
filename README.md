# private-gpt reference snapshot

This repository is a reference snapshot for local experimentation with private document question-answering and retrieval-augmented generation workflows.

It is not presented as the upstream PrivateGPT project.

- **Status:** Reference snapshot
- **Stack:** Python, FastAPI, local RAG components, Gradio UI
- **Problem:** Private document-QA stacks are useful to study locally, but a fork should not be confused with current original product work.

## What this repo is

- A preserved codebase snapshot for local experimentation
- A reference point for private document-QA architecture and API shape
- A comparison artifact alongside newer portfolio work in workflow systems and analysis tooling

## What this repo is not

- It is not the canonical upstream PrivateGPT repository.
- It is not positioned as a current flagship project in this portfolio.
- It should not be read as a claim of authorship over the upstream system design.

## When to use it

Use this repo if you want to inspect:

- a private document-QA API surface
- local ingestion and retrieval patterns
- point-in-time project structure for a PrivateGPT-style stack

For the actively maintained upstream project and current documentation, refer to the upstream PrivateGPT project directly.

## Local use

This snapshot keeps the original project layout, including the Python package, settings files, tests and local model/data folders. Read `pyproject.toml`, `settings.yaml` and the package code under `private_gpt/` if you need to inspect the implementation.
