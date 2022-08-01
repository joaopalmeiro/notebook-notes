# notebook-notes

Personal notes on Jupyter notebooks and other computational notebook platforms.

## Resources

- [Data Science Notebooks](https://datasciencenotebook.org/) website.

## Snippets

### Install packages if on Google Colab

```python
import os

if "COLAB_GPU" in os.environ:
    !pip install feedzai-altair-theme
```

References:

- HERE

## Notes

- `export PIPENV_VENV_IN_PROJECT=1 && pipenv install --python 3.7`.
