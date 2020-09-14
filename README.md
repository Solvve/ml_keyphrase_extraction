# Reviews keyphrase extraction

[![License](http://img.shields.io/badge/license-MIT-green.svg?style=flat)](https://github.com/Solvve/ml_keyphrase-extraction/blob/master/LICENSE)
[![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-378/)
[![Solvve](https://img.shields.io/badge/made%20in-solvve-blue)](https://solvve.com/)

## Description

Unsupervised keyphrase extraction from [Amazon](https://www.amazon.com/) reviews for each product. For solving this problem we follow the next steps:
* Exploratory data analysis
* Clear Data
* Modeling
* Show keyphrases for each product 

## Example of output
Product asin: B01AHB9CN2
* Topic number 1:
    great tablet, tablet price, great tablet price, tablet love, great tablet tablet
* Topic number 2:
    kindle fire, fire hd, kindle fire hd, love kindle, love kindle fire
* Topic number 3:
    easy use, tablet easy, tablet easy use, easy use great, easy use tablet
* Topic number 4:
    tablet great, great tablet great, great price, tablet great price, tablet great tablet
* Topic number 5:
    fire hd8, amazon fire hd8, amazon fire, fire hd8 tablet, hd8 tablet

## Download data
With Kaggle API download [dataset](https://www.kaggle.com/datafiniti/consumer-reviews-of-amazon-products):
```Bash
kaggle datasets download -d datafiniti/consumer-reviews-of-amazon-products
```

## Install all dependencies
Main dependencies:
```bash
pip install -r requirements.txt
```

Optional:
```bash
python -m spacy download en_core_web_lg
```