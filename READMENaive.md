# **Diabetes Prediction Using Naive Bayes and Logistic Regression**

## **Overview**
This project aims to predict diabetes using the Pima Indians Diabetes Database. Various classification models, including **Bernoulli Naive Bayes**, **Gaussian Naive Bayes**, **Multinomial Naive Bayes**, and **Logistic Regression**, were tested to identify the most effective approach.

## **Objectives**
- Analyze factors contributing to diabetes risk.
- Assess model performance in predicting diabetes.
- Suggest improvements for future models.

## **Dataset**
The dataset includes health metrics such as **glucose levels**, **blood pressure**, **BMI**, and **age**, sourced from Kaggle.

## **Process**
1. **Data Cleaning**: Managed missing values, corrected zero values, and scaled features.
2. **Model Training**: Trained models using Naive Bayes variations and Logistic Regression.
3. **Evaluation**: Compared models using accuracy, precision, recall, and confusion matrices.

## **Results**
- **Logistic Regression**: Best performance with **82% accuracy** and high recall for both classes.
- **Gaussian Naive Bayes**: Achieved **79% accuracy**, balanced across both classes.
- **Multinomial Naive Bayes**: Moderate performance, **71% accuracy** with lower recall for diabetes.
- **Bernoulli Naive Bayes**: Struggled with diabetes prediction, **58% accuracy**.


## **Setup**
1. Clone the repository and install dependencies.
2. Run `NaiveBayesReport.ipynb` in Jupyter Notebook to replicate the analysis.
