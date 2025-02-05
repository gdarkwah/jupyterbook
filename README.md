# UW Geospatial Data Analysis Course Jupyterbook

[![Documentation Status](https://readthedocs.org/projects/uwgda-jupyterbook/badge/?version=latest)](https://uwgda-jupyterbook.readthedocs.io/en/latest/?badge=latest)
[![GeoSMART Curricula](https://geo-smart.github.io/assets/curricula_badge.svg)](https://geo-smart.github.io/curriculum)

Latest web version of JupyterBook: https://uwgda-jupyterbook.readthedocs.io

### Local development (for instructors)

#### Environment setup
```
conda create -n uwgdabook jupyter-book
conda activate uwgdabook
```
#### Build book preview
```
jb build book
jb build book --builder linkcheck   #with link checking
```
Note that notebooks are not executed by default (see book/_conf.yaml)

Changes pushed to GitHub are automatically built on RTD. Pull requests generate previews. GitHub Tags result in different versions of the rendered book.
