# Metaflac – FLAC Metadata Editor

Metaflac is a lightweight, cross‑platform **GUI application** for editing the metadata
tags of FLAC audio files.  It is written in **Python 3.13** and packaged with **UV** so it can be
installed and run as a simple command‑line tool.

## Features

- Browse your music library and open any `.flac` file.
- View and edit standard Vorbis comment tags (artist, title, album, year, etc.).
- Add, edit or delete custom tags.
- Preview changes before saving.
- Save changes back to the file with a single click.
- Minimal dependencies – just the Python standard library and `pydub` for audio
  handling.

## Getting Started

### Install

```bash
uv add metaflac
```

### Run

```bash
metaflac
```

This will launch the GUI.  The command is also exposed as a console script
via UV so it can be called from any shell.

## Project Structure

```txt
metaflac/          # Source package
├── __init__.py
└── main.py        # Entry point for the GUI
pyproject.toml      # UV build configuration
```

## Contributing

Feel free to open issues or pull requests.  The project uses `ruff` for linting and
`pytest` for tests.

---
© 2026 RafaxWolf
