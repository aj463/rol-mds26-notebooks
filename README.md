# An Introduction to the Rapid Optimization Library (ROL): SIAM MDS26 minitutorial notebooks

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/aj463/rol-mds26-notebooks/HEAD?urlpath=lab/tree/notebooks)

Interactive notebooks for the minitutorial on ROL's Python interface (`rol-python`). The badge
opens them in JupyterLab on Binder, with nothing to install; each notebook can also be opened on
its own in Binder or Google Colab:

| Notebook | Topic | Open in |
|---|---|---|
| [`01_quickstart_rol`](notebooks/01_quickstart_rol.ipynb) | Exercise A: rank-one matrix completion | [Binder](https://mybinder.org/v2/gh/aj463/rol-mds26-notebooks/HEAD?labpath=notebooks%2F01_quickstart_rol.ipynb) · [Colab](https://colab.research.google.com/github/aj463/rol-mds26-notebooks/blob/main/notebooks/01_quickstart_rol.ipynb) |
| [`02_geometry_rol`](notebooks/02_geometry_rol.ipynb) | Exercise B: the same function, two inner products | [Binder](https://mybinder.org/v2/gh/aj463/rol-mds26-notebooks/HEAD?labpath=notebooks%2F02_geometry_rol.ipynb) · [Colab](https://colab.research.google.com/github/aj463/rol-mds26-notebooks/blob/main/notebooks/02_geometry_rol.ipynb) |

Run the cells in order in a fresh kernel. The first cell installs the `rol-python` release the
notebook was written for; on Binder it is already installed.

A Binder session is temporary: it stops after about ten minutes without activity and does not
keep your changes. Use File > Download to keep a notebook.

## Running locally

With Python 3.12:

    python3.12 -m venv .venv
    .venv/bin/python -m pip install -r requirements.txt jupyterlab
    .venv/bin/jupyter lab notebooks
