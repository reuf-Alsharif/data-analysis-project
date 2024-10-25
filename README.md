 NDiabetes Classification Models
Overview
This project focuses on developing machine learning models to classify individuals as having diabetes or not, based on medical data. The project includes various models such as Bernoulli Naive Bayes, Gaussian Naive Bayes, Multinomial Naive Bayes, and Logistic Regression. The models are evaluated using metrics such as accuracy, precision, recall, and F1-score.

Project Workflow
The steps below outline the full workflow of the project:

1. Data Preprocessing
Loading the dataset: The dataset contains medical features that help predict whether a patient has diabetes.
Data cleaning: Removing any null values, outliers, or irrelevant data.
Feature scaling: Applying normalization or standardization if necessary.
Splitting the data: Dividing the dataset into training and testing sets (e.g., 80% for training and 20% for testing).

3. Model Training
Training different models including:
Bernoulli Naive Bayes
Gaussian Naive Bayes
Multinomial Naive Bayes
Logistic Regression

4. Model Evaluation
After training, each model is evaluated using several performance metrics:
Accuracy: Percentage of correct predictions.
Precision: Proportion of true positive predictions.
Recall: Proportion of actual positive cases identified correctly.
F1-Score: Harmonic mean of precision and recall.
Confusion matrices are generated to analyze the model’s ability to distinguish between "Diabetes" and "No Diabetes."

5. Model Comparison
The models are compared based on their performance metrics:
Model	Accuracy	Precision (Diabetes)	Recall (Diabetes)	F1-Score (Diabetes)

Bernoulli Naive Bayes	58%	0.00	0.00	0.00

Gaussian Naive Bayes	79%	0.67	0.62	0.64

Multinomial Naive Bayes	71%	0.62	0.48	0.54

Logistic Regression	82%	0.76	0.62	0.68

6. Conclusion
Logistic Regression performed best overall, with a balanced accuracy and recall for both classes.
Gaussian Naive Bayes is also a good option, although it is less effective for identifying "Diabetes."
Bernoulli Naive Bayes showed poor performance in identifying "Diabetes" cases.
Multinomial Naive Bayes performed moderately well, but less effective than Logistic Regression.
