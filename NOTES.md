# Notes

- https://github.com/pypa/pipfile

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
