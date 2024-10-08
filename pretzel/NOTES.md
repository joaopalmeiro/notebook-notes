# Notes

- https://github.com/joaopalmeiro/template-python-uv-script
- Pretzel:
  - https://github.com/pretzelai/pretzelai
  - https://pypi.org/project/pretzelai/
  - https://github.com/pretzelai/pretzelai?tab=readme-ov-file#quick-start
  - It supports Ollama
  - https://withpretzel.com/

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

### Clean slate

```bash
rm -rf .ipynb_checkpoints/ .mypy_cache/ .pretzel/ .venv/
```

```bash
rm -rf .ipynb_checkpoints/ .mypy_cache/ .pretzel/ .venv/ *.ipynb
```
