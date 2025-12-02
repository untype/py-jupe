# py-jupe

**py-jupe** is a modern, lightweight starter template for Python data science projects. It is designed to get you from "zero" to "coding in Jupyter" as fast as possible, using the latest tooling.

## Features

*   **⚡️ `uv` for Speed**: Uses `uv` for extremely fast dependency resolution and virtual environment management.
*   **📓 Jupyter-First**: The `jupyter` metapackage is included out of the box, giving you access to Jupyter Lab, Notebook, and IPython immediately.
*   **🧹 Clean Configuration**: Expertly configured `.gitignore` and `pyproject.toml` to keep your repository clean and reproducible.

## Quick Start

To start Jupyter Lab, simply run:

```bash
uv run jupyter lab
```

This command will automatically:
1.  Create a virtual environment (if one doesn't exist).
2.  Install/Sync all dependencies.
3.  Launch the Jupyter Lab interface in your browser.
