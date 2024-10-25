Diabetes Classification Models
Overview
This project involves the development and evaluation of various machine learning models to classify individuals as having diabetes or not. The classification task uses several algorithms, including Naive Bayes (Bernoulli, Gaussian, Multinomial) and Logistic Regression, with performance evaluated through accuracy, precision, recall, and F1-scores.

Models Used
Bernoulli Naive Bayes
Gaussian Naive Bayes
Multinomial Naive Bayes
Logistic Regression
Each model was trained on a dataset with the target of predicting whether an individual has diabetes based on given features.

Dataset
The dataset contains features related to medical records and is divided into two classes: No Diabetes and Diabetes.
Data preprocessing includes removing noise and applying feature scaling where necessary.
Performance Metrics
The following metrics were used to evaluate the models:

Accuracy: The percentage of correct predictions.
Precision: The number of true positives divided by the number of positive predictions.
Recall: The number of true positives divided by the number of actual positives.
F1-Score: The harmonic mean of precision and recall.
Model Comparison
Model	Accuracy	Precision (Diabetes)	Recall (Diabetes)	F1-Score (Diabetes)
Bernoulli Naive Bayes	58%	0.00	0.00	0.00
Gaussian Naive Bayes	79%	0.67	0.62	0.64
Multinomial Naive Bayes	71%	0.62	0.48	0.54
Logistic Regression	82%	0.76	0.62	0.68
From the results, Logistic Regression provided the best performance overall.

