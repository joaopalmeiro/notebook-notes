# Notes

- https://github.com/joaopalmeiro/template-python-uv-script
- Elyra:
  - https://elyra.readthedocs.io/en/latest/getting_started/overview.html#reusable-code-snippets

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
which marimo
```

### Clean slate

```bash
rm -rf .mypy_cache/ .venv/
```
