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

#### References

- [Test if notebook is running on Google Colab](https://stackoverflow.com/questions/53581278/test-if-notebook-is-running-on-google-colab) thread.

### Install packages if on Deepnote

```python
import os

if "DEEPNOTE_PROJECT_ID" in os.environ and "DEEPNOTE_PROJECT_OWNER_ID" in os.environ:
    !pip install altair vega-datasets feedzai-altair-theme
```

#### References

- [Pre-installed packages](https://docs.deepnote.com/environment/pre-installed-packages) documentation.

## Notes

- `export PIPENV_VENV_IN_PROJECT=1 && pipenv install --python 3.7`.
- `pipenv install` + `pipenv run jupyter lab` + `pipenv run black . --verbose`.
