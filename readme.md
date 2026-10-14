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

The project uses two CSV datasets:

- `Fake.csv` - Fake news articles
- `True.csv` - Real news articles

The datasets should be placed in the project directory before running
the notebook.

**Note:** The datasets are not currently included in this repository.
You must obtain them separately and update the file paths if necessary.

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/ArbazAnsari01/Fake-News-Detection.git
