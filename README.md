# C19 Problem Sheets

Notebooks for the C19 problem sheets.

## Contents

- `Reinforcement Learning/windy-grid-world.ipynb`: Windy Grid World (Sutton and Barto, Example 6.5) with Q-Learning, SARSA and Monte-Carlo control.

## Setup

Requires [uv](https://docs.astral.sh/uv/). From the repo root:

```sh
uv sync
```

This creates `.venv/` with Python 3.12 and the packages in `pyproject.toml`.

## Running

In VS Code, open a notebook and pick the `.venv` interpreter as the kernel.

Or in the browser:

```sh
uv run jupyter lab
```

To add a package:

```sh
uv add <package>
```
