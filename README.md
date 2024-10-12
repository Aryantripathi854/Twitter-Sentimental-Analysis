# Sentiment Analysis of Tweets using Logistic Regression

This project focuses on detecting positive and negative tweets using a Logistic Regression model. The dataset is fetched via Kaggle's API, processed for sentiment analysis, and the model is evaluated for accuracy.

## Project Structure
- `kaggle.json`: Configuration file for accessing the Kaggle API.
- `sentiment140.zip`: Compressed dataset containing 1.6 million tweets.
- `training.1600000.processed.noemoticon.csv`: Processed CSV file with labeled tweets.
- `trained_model.sav`: The saved trained Logistic Regression model.
- `logistic_regression_sentiment_analysis.ipynb`: The main Jupyter notebook containing the code.

## Dependencies
- Python 3.x
- Libraries:
  - `numpy`
  - `pandas`
  - `nltk`
  - `sklearn`
  - `kaggle`
  - `pickle`

## How to Run
1. Install required libraries:
2. pip install kaggle numpy pandas nltk scikit-learn
3. 2. Place `kaggle.json` in the correct directory for API access.
3. Download the dataset using the Kaggle API.
4. Run the Jupyter notebook to preprocess the dataset, train the model, and evaluate the performance.
5. The final trained model can be saved and loaded using `pickle` for future predictions.

## Results
- Accuracy on training data: **79.871953125%**
- Accuracy on test data: **77.668125%**

## Dataset
The dataset used is the Sentiment140 dataset, containing 1.6 million tweets labeled as either positive or negative.
- 0: Negative Sentiment
- 1: Positive Sentiment

## Model
Logistic Regression is used as the model for binary classification of sentiments.


