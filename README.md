# Crafty-Snap
an automated Snapcraft generator that builds snap packages from your project’s metadata.

## Why this exists

Let’s be honest: the Snap Store is struggling, and a big part of the problem is how difficult it is to create snaps. The rules are strict, the documentation is scattered, and there’s no real guide that explains how to package modern apps without losing your mind.

I’m a massive Canonical fan — truly — but Snapcraft dropped the ball here. Most projects already have metadata files like `pyproject.toml`, `requirements.txt`, `Cargo.toml`, or `package.json`. Snapcraft *should* have been able to use these to generate a working `snapcraft.yaml`. That’s a reasonable expectation.

So Crafty‑Snap aims to fill that gap.

Right now the repo is empty, but the goal is to build a tool that reads your project’s metadata and generates a snapcraft.yaml automatically. If this works, maybe we’ll finally see more snaps in the store.

This is one of those “I can’t promise anything, but I’m giving it a shot” projects.

## Roadmap

- **pyproject.toml**
  - Start with Python + PySide6 support (the easiest place to begin)
- **requirements.txt**
  - Natural extension of Python support
- **Cargo.toml**
  - Rust has similar structure and is easy to parse
- **package.json**
  - The big one — needed for SnapDock and other Electron/Node apps

## Expectations

Like I said, I don’t expect miracles. But if Canonical isn’t going to solve this problem, I might as well try.

## STANDARDS

Because Crafty‑Snap is still in early R&D, it is not required to follow the full [ZFordDev standards](https://github.com/ZFordDev/ZFordDev/blob/main/STANDARDS.md) at this stage.
