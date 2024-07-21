# smallbird-site

## Reference

- [github-repo](https://github.com/tishenme/smallbird-site)
- [github-page](https://tishenme.github.io/smallbird-site)

## Guideline

- 官方教程

  - [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/getting-started/)

- 参考博客

  - [未央学习](https://weyoung-learn.github.io/skills/mkdocs/)
  - [Eureka!](http://www.cuishuaiwen.com:8000/zh/PROJECT/TECH-BLOG/mkdocs_and_material/)

  - [Cloud Notes](https://notes.lzwang.ltd/Python/)
  - [create-blog](https://github.com/mkdocs-material/create-blog/blob/main/mkdocs.yml)

```bash

# venv_conda_39_mkdocs
conda deactivate
conda remove -n venv_conda_39_mkdocs --all -y
conda create python=3.9.13 -n venv_conda_39_mkdocs -y
conda activate venv_conda_39_mkdocs
python.exe -m pip install --upgrade pip
pip install --upgrade pip
pip install --upgrade setuptools
pip list

# install
conda activate venv_conda_39_mkdocs
pip install -r requirements.txt

# # upgrade
# conda activate venv_conda_39_mkdocs
# pip install --upgrade --force-reinstall mkdocs-material
# pip show mkdocs-material

# help
conda activate venv_conda_39_mkdocs
mkdocs --help

# init project
cd D:\CodeWork\IDE_Microsoft_VSCode_Workspace
conda activate venv_conda_39_mkdocs
mkdocs new smallbird-site

# Build the website
conda activate venv_conda_39_mkdocs
mkdocs build

# Run the website
conda activate venv_conda_39_mkdocs
mkdocs serve

```
