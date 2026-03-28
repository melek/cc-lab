# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

Plugins are referenced by GitHub source in `marketplace.json` — no code lives in this repo. Each plugin's source repo is `melek/<plugin-name>`.

- **Bump version in `plugin.json`** in the source repo for every change — the plugin cache won't update without it.
- Validate before publishing: `claude plugin validate .`
