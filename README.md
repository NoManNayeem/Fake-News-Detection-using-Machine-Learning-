# Fake News Detection using Machine Learning Models

This project focuses on classifying a dataset containing the following features: 'Title', 'Text', 'Author', and 'Label'. The 'Label' column represents the target variable, with 0 indicating true and 1 indicating false.

## Machine Learning Models Used

We have employed the following machine learning models to perform classification and compare their accuracy:

1. SVM (Support Vector Machines)
2. Random Forest
3. NLP-MNB (Naive Bayes with Multinomial Feature Representation)
4. XGBoost
5. Logistic Regression
6. MNB (Multinomial Naive Bayes)

## Model Descriptions

### 1. SVM (Support Vector Machines)

Support Vector Machines is a powerful supervised learning algorithm used for both classification and regression tasks. SVM constructs a hyperplane or set of hyperplanes in a high-dimensional space that can be used for classification. It aims to maximize the margin between classes, thereby achieving good generalization.

### 2. Random Forest

Random Forest is an ensemble learning method that combines multiple decision trees to create a robust and accurate model. It builds a collection of decision trees and outputs the class that is the mode of the classes predicted by individual trees. Random Forest is known for its ability to handle high-dimensional data and maintain good performance.

### 3. NLP-MNB (Naive Bayes with Multinomial Feature Representation)

NLP-MNB is a variant of the Naive Bayes algorithm specifically designed for text classification tasks. It utilizes the multinomial feature representation, which is suitable for discrete features such as word counts. NLP-MNB applies Bayes' theorem with the assumption of independence between features and predicts the class with the highest probability.

### 4. XGBoost

XGBoost (Extreme Gradient Boosting) is an efficient implementation of the gradient boosting algorithm. It is widely used for classification and regression tasks and often yields state-of-the-art results. XGBoost constructs an ensemble of weak prediction models (typically decision trees) and iteratively improves their performance by minimizing a loss function.

### 5. Logistic Regression

Logistic Regression is a popular statistical model used for binary classification problems. Despite its name, it is a classification algorithm rather than a regression algorithm. Logistic Regression models the relationship between the dependent variable and one or more independent variables using the logistic function, which maps the output to a probability value.

### 6. MNB (Multinomial Naive Bayes)

Multinomial Naive Bayes is another variant of the Naive Bayes algorithm suitable for text classification. It assumes that the features (words or other discrete features) follow a multinomial distribution. MNB estimates the probabilities of each class based on the presence and frequency of features, making it efficient and effective for large-scale text classification tasks.

## Conclusion

In this project, we have utilized various machine learning models, including SVM, Random Forest, NLP-MNB, XGBoost, Logistic Regression, and MNB, to classify a dataset with 'Title', 'Text', 'Author', and 'Label' features. By comparing their accuracy, we can gain insights into the performance of each model and identify the most suitable approach for our specific classification task.
