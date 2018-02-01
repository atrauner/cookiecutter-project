{{cookiecutter.project_name}}
==============================

{{cookiecutter.description}}

Hypothesis:
------------
{{cookiecutter.hypothesis}}

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical datasets.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── notebooks          <- Exploratory notebooks. Naming convention is a number (for ordering),
    │   │                     the creator's initials, and a short `-` delimited description, e.g.
    │   │                     `1.0-ATR-general-data-overview.ipynb`.
    │   │
    |   └── `0.0-ATR-blank-template.ipynb`
    |
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data.
    │   │   ├── make_dataset.py          <- Get data from source - e.g. server, zenodo
    │   │   └── refactored_analysis.py   <- Refactor key steps from the exploratory analysis.
    │   │
    │   ├── external       <- External scripts ran for data analysis e.g. shell scripts.
    │   │
    │   │
    │   └── visualization  <- Scripts to create exploratory and results
    │       │                 oriented visualizations refactored from the
    │       │                 notebooks and based on processed data generated
    │       │                 by `run_analysis.py`
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.testrun.org

Data location
------------
{{cookiecutter.data}}
