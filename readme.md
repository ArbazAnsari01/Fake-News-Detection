# Fake News Detection Using Machine Learning

## Project Overview

This project uses Natural Language Processing (NLP) and machine learning
techniques to classify news articles as Fake News or Real News.

The system preprocesses news text, converts it into numerical features
using TF-IDF vectorization, and predicts the news category using
multiple machine learning classification models.

## Features

- Text preprocessing and cleaning
- TF-IDF feature extraction
- Training and testing machine learning models
- Classification report and accuracy evaluation
- Manual testing of news articles
- Comparison of predictions from multiple models

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Jupyter Notebook

## Machine Learning Models

The project uses the following classification algorithms:

1. Logistic Regression
2. Decision Tree Classifier
3. Gradient Boosting Classifier
4. Random Forest Classifier

The models predict whether the supplied news article is fake or real.

## Dataset

This project uses the Fake and Real News Dataset from Kaggle.

**Dataset Link:** [Download the dataset from Kaggle](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

The dataset contains two CSV files:

- `Fake.csv` — Fake news articles
- `True.csv` — Real news articles

### Dataset Setup

1. Open the Kaggle dataset link above.
2. Sign in to Kaggle if required.
3. Download the dataset.
4. Extract the downloaded files.
5. Place `Fake.csv` and `True.csv` in the project directory.

**Note:** The dataset files are not stored in this GitHub repository because they exceed GitHub's browser upload limit.

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/ArbazAnsari01/Fake-News-Detection.git
