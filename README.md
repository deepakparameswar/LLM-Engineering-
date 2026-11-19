# llm-notebooks

A Python notebook project managed with [uv](https://docs.astral.sh/uv/).

## Get started

```powershell
uv sync --dev
uv run jupyter lab
```

Open `notebooks/analysis.ipynb` in JupyterLab or VS Code. In VS Code, select the
project's `.venv` Python interpreter as the notebook kernel.

Add project packages with:

```powershell
uv add <package>
```

Add development tools with:

```powershell
uv add --dev <package>
```

The `uv.lock` file records exact dependency versions for reproducible installs.
