# Sentiment Analysis Project

## Overview
This project aims to perform sentiment analysis on a dataset of reviews. The objective is to classify the sentiment of each review as positive, negative, or neutral.

## Dataset
- **Dataset**: [Dataset on Kaggle](https://www.kaggle.com/datasets/dolbokostya/test-dataset/data)
- **Description**: The dataset consists of reviews, topics, and scores for each review.

## Usage

### Installation
To install the necessary package dependencies, use [UV](https://pypi.org/project/uv/):

```sh
uv install

uv sync
```

Running the Analysis
To run the analysis, open the analysis.ipynb notebook in Jupyter and execute the cells.

## Project Structure
.
├── .python-version
├── 2.5m-reviews-dataset.csv
├── analysis.ipynb
├── pyproject.toml
├── README.md
├── requirements.txt
└── uv.lock

## Dependencies
ipykernel>=6.29.5
nltk>=3.9.1
pandas>=2.2.3
scikit-learn>=1.6.1
scipy>=1.15.1
wordcloud>=1.9.4