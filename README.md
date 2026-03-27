# Useful Resources

This repository provides links to resources that I have found helpful throughout my Ph.D. journey or have made myself. Graduate students and research assistants may find these particularly helpful. The secundary goal of it is to help me when configuring future setups or when trying to remember some important (and often obscure) reference. This repository was inspired by many others, like the ones done by [Ricardo Dahis](https://github.com/rdahis) and [Vinícius Hector](https://github.com/HecVini).

## Python

1. [`uv`](https://docs.astral.sh/uv/): This is my prefered package and environment manager for Python. Install it with `pip install uv`. You can create projects with `uv init my_project`, generate an environemnt with `uv venv`, and add packages with `uv add my_package`.

2. [`geospatial`](https://geospatial.gishub.org/): This package installs virtually all the geospatial data analysis tools/packages you will ever need. This is particularly useful to me because geopandas is notoriously difficult to install outside conda installations. Add it to your project with `uv add geospatial`.

4. [`joblib`](https://joblib.readthedocs.io/en/stable/): This package saves you so much time that its insane. Cache your variables and parallelize your code.

5. [`dask`](https://www.dask.org/): Scale all of your `pandas` knowledge to work with big data, reading dataframes in lazy mode. It can be a life savior in lower end machines.

6. [`dask-geopandas`](https://dask-geopandas.readthedocs.io/en/stable/): Similar to `dask`, but for GIS data.

7. [`df-compress`](https://pypi.org/project/df-compress/): My attempt at replicating the behavior of Stata's `compress` command in Python.

## Julia
1. [Geospatial Data Science with Julia](https://juliaearth.github.io/geospatial-data-science-with-julia/): The single best resource for you to start your geospatial data analysis journey in Julia.

2. [QSE Model in Julia](https://github.com/phchavesmaia/QSE-models): These are my attempts at running QSE models in Julia. The goal is to discuss the steps and decisions made by the authors while replicating their findings.
