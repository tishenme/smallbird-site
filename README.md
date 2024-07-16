# smallbird-site

## Reference

- [github-repo](https://github.com/tishenme/smallbird-site)
- [github-page](https://tishenme.github.io/smallbird-site)

## Guideline

[Material for MkDocs](https://squidfunk.github.io/mkdocs-material/getting-started/)
[create-blog](https://github.com/mkdocs-material/create-blog/blob/main/mkdocs.yml)

```shell

# venv_conda_39_mkdocs
conda remove -n venv_conda_39_mkdocs --all -y
conda create python=3.9.13 -n venv_conda_39_mkdocs -y
conda activate venv_conda_39_mkdocs
pip list
pip install --upgrade pip
pip install --upgrade setuptools

# install
pip install mkdocs-material
pip install mkdocs-material=="9.*"
pip install mkdocs-material=="9.5.27"

# upgrade
pip install --upgrade --force-reinstall mkdocs-material
pip show mkdocs-material

# help
mkdocs --help

# init project
conda activate venv_conda_39_mkdocs
cd D:\CodeWork\IDE_Microsoft_VSCode_Workspace
mkdocs new smallbird-site

# publish
conda activate venv_conda_39_mkdocs
mkdocs serve

```
