# Poetry Cookie Cutter

A minimalist cookie-cutter template for data-science using Python and poetry.


Based mostly on the structure described [here](https://goodresearch.dev/setup.html).


## Installation

```sh
cookiecutter gh:niklasdewally/poetry-ds-cookiecutter
```


## Structure and Opinions

```shell
├── LICENSE
├── Makefile           <- Makefile with commands like `make data` or `make train`
├── README.md     
├── pyproject.toml     <- Poetry and python package info
├── .gitignore        
├── data               <- By default, this is not backed up in version control
│   ├── raw            <- The original, immutable data dump.
│   ├── interim        <- Intermediate data that has been transformed.
│   └── processed      <- The final, canonical data sets for modeling.
│
├── docs               
│
├── results            <- Reports, models, generated data, etc.
│
├── src                <- Source code for use in this project to be imported as a library in python.
│   ├── __init__.py    
│
├── scripts        <- Executable bash, python, etc. scripts
│   │
│   ├── data           <- Scripts to download or generate data
│   │   └── make_dataset.py
│   │
│   ├── features       <- Scripts to turn raw data into features for modeling
│   │   └── build_features.py
│   │
│   ├── models         <- Scripts to train models and then use trained models to make
│   │   │                 predictions
│   │   ├── predict_model.py
│   │   └── train_model.py
│   │
│   └── visualization  <- Scripts to create exploratory and results oriented visualizations
│       └── visualize.py
```


This project is, in essence,
[true-neutral-cookie-cutter](https://goodresearch.dev/setup.html#create-a-project-skeleton)
with a `Makefile` and poetry.


