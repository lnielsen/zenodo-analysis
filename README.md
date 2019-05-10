# Zenodo metadata analysis notebook

## Install

```
$ mkvirtualenv notebook
(notebook)$ cd ~/src/zenodo-analysis/
(notebook)$ pip install -r requirements.txt
```

## Download a dump

```
$ wget https://zenodo.org/api/files/00000000-0000-0000-0000-000000000001/records-2019-05-01T04:00:00.json.bz2
$ bunzip2 records-2019-05-01T04:00:00.json.bz2
```

## Run

```
(notebook)$ jupyter-notebook notebook.ipynb
```
