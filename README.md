# **Text Analysis Project**

## **Overview**
This project evaluates various **text classification** models on a dataset of news articles labeled as real or fake. It includes **Naive Bayes** and **Logistic Regression** models, with analysis focusing on identifying meaningful features and improving detection accuracy.

## **Objectives**
- Detect fake news using text classification models.
- Compare performance across different models and feature representations.

## **Dataset**
The dataset contains labeled articles with attributes like **title**, **text**, **author**, and **label** (0 for real, 1 for fake). It is sourced from [Kaggle's Fake News Dataset](https://www.kaggle.com/c/fake-news/data).

## **Process**
1. **Data Cleaning**: Removed duplicates, handled missing values, standardized text, and removed stopwords.
2. **Exploratory Analysis**: Examined text length distributions and common word frequencies across categories.
3. **Sentiment Analysis**: Compared **TextBlob** and **VADER** for sentiment classification.
4. **Model Evaluation**: Trained Naive Bayes (Bernoulli, Gaussian, Multinomial) and Logistic Regression, comparing **TF-IDF** and **Bag of Words (BoW)** representations.

## **Results**
- **Logistic Regression (TF-IDF + Bigrams)**: Highest accuracy at **81.88%**.
- **MultinomialNB (BoW)**: Accuracy of **78.69%**, better suited for negative sentiment.
- **BernoulliNB (TF-IDF)**: Achieved **73.80%** accuracy but struggled with positive classification.
- **ComplementNB (TF-IDF)**: Good performance with **73.36%** accuracy, effective for imbalanced datasets.

## **Key Metrics**
- **Support**: Minimum 1% (item presence).
- **Confidence**: Minimum 50%.
- **Lift**: Values >1 indicate strong associations.


## **Setup**
1. Clone repository and install dependencies.
2. Run `TextAnalysis.ipynb` in Jupyter Notebook for analysis.
