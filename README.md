# Yelp Reviews Prediction

## Introduction
This project uses a small subset of the data from Kaggle's **Yelp Business Rating Prediction** competition. The goal is to predict the star rating (1 through 5 stars) of a review based on the text content of the review itself.

## Data Description
The dataset used in this project is `yelp.csv` and is stored in the `data` directory of this repository. It contains the following columns:

- **stars**: The number of stars assigned by the reviewer to the business (ranging from 1 to 5). Higher star ratings indicate better reviews.
- **text**: The text content of the review. This is the key feature that we use to predict the star rating.

Each row represents an individual review for a particular business, written by a specific user.

## Goal
The main objective of this project is to predict the star rating of a review based solely on the **text** of the review. We will leverage natural language processing (NLP) techniques and machine learning models to solve this problem.

## Approach
1. **Data Preprocessing**: Clean and preprocess the text data (e.g., removing stop words, punctuation, and normalizing text).
2. **Vectorization**: Convert the text data into numerical form using techniques like `CountVectorizer` or `TfidfVectorizer`.
3. **Model Building**: Build a machine learning model (e.g., Naive Bayes, Logistic Regression, etc.) to predict the star rating.
4. **Evaluation**: Evaluate the model's performance using appropriate metrics such as accuracy, precision, recall, or F1 score.

## Technologies Used
- **Python 3.x**
- **pandas** for data manipulation
- **scikit-learn** for machine learning models and preprocessing
- **matplotlib** and **seaborn** for data visualization
- **Jupyter Notebook** for exploring the data and running code

## Installation

To run the project, you will need to install the following dependencies:

```bash
pip install pandas scikit-learn matplotlib seaborn
