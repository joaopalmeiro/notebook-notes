# Notes

- https://github.com/joaopalmeiro/template-python-uv-script
- marimo:
  - https://marimo.io/
  - https://github.com/marimo-team/marimo?tab=readme-ov-file#quickstart
  - https://pypi.org/project/marimo/
  - https://docs.marimo.io/
  - https://docs.marimo.io/guides/editor_features/overview.html#overview-panels:
    - "snippets - searchable snippets to copy directly into your notebook"
  - https://github.com/marimo-team/marimo/tree/0.8.15/marimo/_snippets/data
  - https://github.com/marimo-team/marimo/blob/0.8.15/frontend/src/components/editor/chrome/panels/snippets-panel.tsx#L61-L65
  - https://github.com/marimo-team/marimo/blob/0.8.15/frontend/src/components/ui/command.tsx#L63
  - https://github.com/marimo-team/marimo/blob/0.8.15/frontend/src/components/editor/chrome/panels/snippets-panel.tsx#L193-L212
  - https://github.com/pacocoursey/cmdk
- https://github.com/pallets/itsdangerous/

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
rm -rf .mypy_cache/ .venv/ *.py
```
