# nbclassic: Jupyter Notebook as a Jupyter Server Extension

![Testing nbclassic](https://github.com/Zsailer/nbclassic/workflows/Testing%20nbclassic/badge.svg)

This library allows you to install both [jupyter/notebook](github.com/jupyter/notebook) and a Jupyter Notebook Server Extension side-by-side (and any other Jupyter Server Frontend).

This helps projects like JupyterLab and nteract_on_jupyter transition from jupyter/notebook to jupyter/jupyter_server for the core Jupyter Tornado Server.

## Install

Install from PyPI:
```
pip install nbclassic
```

Launch with Jupyter Server:
```
jupyter server
```
or directly with
```
jupyter nbclassic
```
and go to: http://localhost:8888/tree?token=...
