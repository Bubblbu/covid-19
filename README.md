# Explore Covid-19

Just a barebones project template to explore Covid-19 data with Jupyter notebooks.

## Getting started

**Recommeded way**

Use [Poetry](https://python-poetry.org/docs/) to manage Python versions and dependencies. To do so, follow instructions on to install Poetry (Python 3.6 required).

After cloning this repository, simply run `poetry install` to install the virtualenv in the local project folder.

`poetry shell` will activate the virtual environment.

`python -m ipykernel install --user --name="corona"` will make the kernel available to Jupyterlab.

**Optional**

Alternatively, you can simply use good ol' `pip install -r requirements.txt`.

## Acknowledgements

The data is provided by [`pyCOVID`](https://github.com/sudharshan-ashok/pycovid). Please refer to its documentation for more instructions on how to access the underlying data.
