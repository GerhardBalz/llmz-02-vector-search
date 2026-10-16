# llmz-02-vector-search

LLM Zoomcamp 2026 — Homework 2: Vector Search.

## Status

Public starter repository and dedicated Codespace created on 16 October 2026 (Europe/Zurich), with Gerhard's explicit authorization. No homework question has been executed or answered. Completed-solution publication and course submission remain deferred for later review.

Each homework has its own repository and Codespace. Homework 1's workspace remains separate.

- Codespace: **friendly palm-tree**.
- [Open the Homework 2 Codespace](https://friendly-palm-tree-x5gvr9rrpq4h9xxj.github.dev/).
- Workspace: `/workspaces/llmz-02-vector-search`.
- Setup verified on 16 October 2026 (Europe/Zurich): trusted workspace, Python 3.12.3 in the project virtual environment, uv 0.13.1, registered LLMZ Homework 2 kernel, installed dependencies and successful CPU ONNX model loading. See [setup evidence](setup-evidence.json) for versions, model revision and file hashes. The notebook remains unexecuted.
- The startup-created local poetry.lock is preserved untracked; uv.lock is this project's dependency lock.

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
- The official downloader uses the model repository's default revision. The verified local download resolved to revision 751bff37182d3f1213fa05d7196b954e230abad9; [setup-evidence.json](setup-evidence.json) records both file hashes. Model files are kept locally and ignored by Git.

## Environment setup (administration)

Use a fresh project environment. Python 3.12 is selected for this project; Homework 1's Conda environment remains separate. The course does not prescribe a Python version or fixed dependency versions.

With `uv` available, run from the repository root:

```bash
uv sync --locked
uv run python -m ipykernel install --user --name llmz-hw2 --display-name "LLMZ Homework 2"
uv run python download.py
```

The committed `uv.lock` records the installed dependency versions. Runtime imports, official helper hashes, notebook schema, kernel interpreter and CPU model loading have been verified. Model files and virtual environments are ignored by Git.

Open `homework-02.ipynb`, select **LLMZ Homework 2**, and run only the environment-check cell. Continue one small learning cell at a time in chat; Q1–Q6 remain for learner execution.
