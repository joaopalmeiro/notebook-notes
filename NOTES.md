# Notes

- https://github.com/pypa/pipfile
- https://plutojl.org/:
  - https://github.com/fonsp/Pluto.jl
- https://pieces.app/:
  - https://github.com/pieces-app/jupyter-pieces
  - https://pieces.app/plugins/jupyterlab
  - https://docs.pieces.app/extensions-plugins/jupyterlab
  - https://docs.pieces.app/installation-getting-started/pieces-os
  - https://docs.pieces.app/installation-getting-started/what-am-i-installing
- https://moonglow.ai/:
  - https://www.youtube.com/watch?v=Bf-xTsDT5FQ
- https://github.com/comet-ml/kangas
- https://elicit.com/
- https://www.zerve.ai/
- https://curvenote.com/
- https://danmackinlay.name/notebook/jupyter.html
- https://starboard.gg/:
  - https://github.com/gzuidhof/starboard-notebook
- https://www.typecell.org/:
  - https://github.com/TypeCellOS/TypeCell
  - https://www.blocknotejs.org/
  - https://github.com/TypeCellOS/BlockNote

## Commands

- `export PIPENV_VENV_IN_PROJECT=1 && pipenv install --python 3.7`
- `pipenv install` + `pipenv run jupyter lab` + `pipenv run black . --verbose`

## Snippets

### `.vscode/settings.json` file

```json
{
  "python.defaultInterpreterPath": "${workspaceFolder}/.venv/bin/python3.7"
}
```

### `Pipfile`

```toml
[[source]]
url = "https://pypi.org/simple"
verify_ssl = true
name = "pypi"

[packages]
black = {extras = ["jupyter"], version = "*"}
isort = "*"
jupyterlab = "*"

[dev-packages]

[requires]
python_version = "3.7"
```
