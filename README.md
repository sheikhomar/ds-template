# Data Science Project Template

A template repository for data science projects. 

The file organisation is based losely on [TDSP Project Structure](https://github.com/Azure/Azure-TDSP-ProjectTemplate) and [CookieCutter Data Science](https://github.com/drivendata/cookiecutter-data-science/).

## Development Setup

1. Clone Git repository.
2. Install [pyenv](https://github.com/pyenv/pyenv):
   ```bash
   curl https://pyenv.run | bash
   ```
3. Install and activate the Python version:
   ```bash
   pyenv install
   ```
4. Install [Poetry](https://python-poetry.org/docs/).
   ```bash
   curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python
   source $HOME/.poetry/env
   ```
5. Install dependencies
   ```bash
   poetry install
   ```