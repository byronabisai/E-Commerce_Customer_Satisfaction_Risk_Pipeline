E-Commerce Customer Satisfaction Risk Pipeline

Overview

This project develops a machine learning pipeline to identify customers at risk of reporting low satisfaction based on e-commerce customer behavior and interaction data.

The project covers data preprocessing, exploratory analysis, feature engineering, model development, evaluation, and business interpretation.

Objectives

Analyze customer behavior and satisfaction patterns

Identify factors associated with low customer satisfaction

Build a reproducible machine learning pipeline

Evaluate classification performance

Determine whether the available data provides useful predictive signal

Generate practical business recommendations

Methodology

Data loading and understanding

Data quality assessment

Data preprocessing

Exploratory Data Analysis

Feature engineering

Machine learning model development

Model evaluation

Statistical/permutation testing

Business interpretation

Machine Learning

A HistGradientBoosting classifier was evaluated to predict low customer satisfaction.

The target variable was defined as a customer rating of ≤ 2.0, representing potentially dissatisfied customers.

Evaluation

The model was evaluated using:

ROC-AUC

Classification performance

Permutation testing

Feature importance analysis

The model achieved a test ROC-AUC of approximately 0.49. Permutation testing also indicated that the predictive performance was not statistically significant.

Key Finding

The available features did not provide sufficient predictive information to reliably identify dissatisfied customers.

Therefore, deploying the model as a customer satisfaction risk system would not be recommended. Additional behavioral, transactional, and customer-experience data should be collected before developing a predictive solution.

Technologies

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

Conclusion

This project demonstrates the importance of validating machine learning models rather than relying solely on model performance. The analysis found insufficient predictive signal in the available data, highlighting the need for better features and richer customer data before deployment.
