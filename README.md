# IC2Classic API Sources

This repository is a **clean, API‑only** fork of master branch (1.12.2) of the original [IC2Classic](https://github.com/TinyModularThings/IC2Classic) repository.  
It contains **only the API source files** – no bug tracker, no mod implementation, no test code, and no extra assets.

## Purpose

The sole purpose of this repository is to provide **machine‑readable API sources** that can be used by AI tools (such as DeepWiki) to generate accurate, up‑to‑date documentation for:

- **IC2 API** – The original IndustrialCraft 2 Experimental API, kept for compatibility with other mods that rely on it.
- **IC2Classic API** – The dedicated API written specifically for IC2Classic.

## Relationship to the Original Repository

- **Original repository:** [TinyModularThings/IC2Classic](https://github.com/TinyModularThings/IC2Classic) – includes bug tracker, full mod code, and both APIs.
- **This fork:** Extracted only the API source files (`src/main/java` for the API packages), removing all non‑API content.

## Contents

- `src/main/java/ic2/api/` – IC2 Experimental API (compatibility layer)
- `src/main/java/ic2/api/classic/` – IC2Classic native API

## Usage for LLM / Documentation Tools

Point your documentation generator (e.g., DeepWiki, JavaDoc, or any AST parser) directly to the `src/` directory. The code is structured exactly as it appears in the original mod, so any tool that understands Java source files can process it without modification.

## Permissions & License

This repository inherits the same licensing and permissions as the original IC2Classic project.  

## No Bug Tracker / Support

This is **not the place** to report bugs or request features for IC2Classic.  
Please use the [official IC2Classic issue tracker](https://github.com/TinyModularThings/IC2Classic/issues) instead.
