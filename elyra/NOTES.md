# Notes

- https://github.com/joaopalmeiro/template-python-uv-script
- Elyra:
  - https://elyra.readthedocs.io/en/latest/getting_started/overview.html#reusable-code-snippets
  - https://elyra.readthedocs.io/en/latest/user_guide/code-snippets.html
  - https://elyra.readthedocs.io/en/latest/getting_started/installation.html
  - https://pypi.org/project/elyra/
  - https://github.com/elyra-ai/elyra/blob/v3.15.0/pyproject.toml#L28: `"jupyterlab>=3.4.6,<4.0"`

## Commands

```bash
deactivate && uv venv .venv && source .venv/bin/activate && uv pip install -r requirements.txt
```

```bash
uv venv .venv && source .venv/bin/activate && uv pip install -r requirements.txt
```

```bash
echo "Cache directory:" && uv cache dir && \
echo "\nTool directory:" && uv tool dir && \
echo "\nPython directory:" && uv python dir
```

```bash
which jupyter
```

### Clean slate

```bash
rm -rf .ipynb_checkpoints/ .mypy_cache/ .venv/ .virtual_documents/
```

```bash
rm -rf .ipynb_checkpoints/ .mypy_cache/ .venv/ .virtual_documents/ *.ipynb *.pipeline *.r
```
