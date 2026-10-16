# llmz-02-vector-search

LLM Zoomcamp 2026 — Homework 2: Vector Search.

## Status

Public starter repository and dedicated Codespace created on 16 October 2026 (Europe/Zurich), with Gerhard's explicit authorization. No homework question has been executed or answered. Completed-solution publication and course submission remain deferred for later review.

Each homework has its own repository and Codespace. Homework 1's workspace remains separate.

- Codespace: **friendly palm-tree**.
- [Open the Homework 2 Codespace](https://friendly-palm-tree-x5gvr9rrpq4h9xxj.github.dev/).
- Workspace: `/workspaces/llmz-02-vector-search`.
- Setup checkpoint: the editor and starter files are visible. VS Code's folder-trust prompt blocks terminal access. Package installation, Python runtime checks, model download and kernel setup have not yet been performed.

## Core links

- [Course portal and Homework 2 submission](https://courses.datatalks.club/llm-zoomcamp-2026/homework/hw2).
- [Module 2 — Vector Search lessons](https://github.com/DataTalksClub/llm-zoomcamp/tree/main/02-vector-search).
- [Current Homework 2 requirements](https://github.com/DataTalksClub/llm-zoomcamp/blob/main/cohorts/2026/homework/02-vector-search/homework.md).
- [Homework notebook](homework-02.ipynb).

## Requirements and provenance

- [Homework 2 requirements inspected for setup](https://github.com/DataTalksClub/llm-zoomcamp/blob/1c42efbeb8141c183e7ae51698ad912c70c06a06/cohorts/2026/homework/02-vector-search/homework.md).
- Dataset: 72 markdown lesson pages at `8c1834d114754cc0e0d65544b8589ef7d94b81cf`, using the `/lessons/` filter and original filenames.
- Model: `Xenova/all-MiniLM-L6-v2`, CPU ONNX runtime, 384 dimensions.
- Official helpers copied unchanged from course commit `1c42efbeb8141c183e7ae51698ad912c70c06a06`, under `02-vector-search/embed/`. Some homework setup links still use an obsolete `cohorts/2026/` prefix.
- `download.py` source blob: `8640a09f38f61de86b96bb60a0042552ee79bf23`.
- `embedder.py` source blob: `db70ba8a124f8e91de2957001dda41e81ebe551e`.
- The official downloader uses the model repository's default revision. Record the resolved model revision and file hashes when downloading. Model files have not yet been downloaded or verified.

## Environment setup (administration)

Use a fresh project environment. Python 3.12 is selected for this project; Homework 1's Conda environment remains separate. The course does not prescribe a Python version or fixed dependency versions.

With `uv` available, run from the repository root:

```bash
uv sync
uv run python -m ipykernel install --user --name llmz-hw2 --display-name "LLMZ Homework 2"
uv run python download.py
```

Retain the generated `uv.lock` for reproducibility. Dependencies have not been installed or runtime-verified yet. Model files and virtual environments are ignored by Git.

Open `homework-02.ipynb`, select **LLMZ Homework 2**, and run only the environment-check cell. Continue one small learning cell at a time in chat; Q1–Q6 remain for learner execution.
