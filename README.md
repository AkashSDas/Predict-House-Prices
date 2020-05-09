# Predict House Prices

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
[![](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/AkashSDas)
[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://github.com/AkashSDas)
[![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)](LICENSE)


## Table of contents

* [About](#about)
* [Installation](#installation)
* [Acknowledgments](#acknowledgments)
* [Data Source](#data-source)
* [License](#license)


## About

>In this project **Ames Housing dataset**  is used, which has **79 features** and 1 target variable i.e. SalePrice(house prices) and did **feature engineering** to see which features are relevant in predicting the house price and created a **machine learning model** which will take relevant features(selected while feature engineering) as input and give prediction of what might be the price of that house as output.


## Installation

It is highly **recommended** to use **`virtual enviroment`** for this project to avoid any issues related to dependencies.

Here **`pipenv`** is used for this project.

There is a **`requirements.txt`** file in `'Predict-House-Prices'/requirements.txt` which has all the dependencies for this project.

- First, start by closing the repository

```bash
git clone https://github.com/AkashSDas/Predict-House-Prices
```

- Start by installing **`pipenv`** if you don't have it
```bash
pip install pipenv
```

- Once installed, access the venv folder inside the project folder
```bash
cd 'Predict-House-Prices'/venv/
```

- Create the virtual environment
```bash
pipenv install
```
The **Pipfile** of the project must be for creating replicating project's virtual enviroment.

This will install all the dependencies and create a **Pipfile.lock** (this should not be altered).

- Enable the virtual environment
```bash
pipenv shell
```

- dataset, jupyter notebook and model are in `'Predict-House-Prices'/requirements.txt/src` folder.

```bash
cd src/
```

- To start/view the jupyter notebook
```bash
jupyter noterbook
```

This will open a webpage in the browser from there you can click on notebook.ipynb to view it.


## Acknowledgments

The **Ames Housing dataset** was compiled by **Dean De Cock** for use in data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset.

## Data Source

This dataset can found in Kaggle - [Source](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

## License

This project is licensed under the MIT License - see the  [MIT LICENSE](LICENSE)  file for details.
