# Chapter-5-exercises
This repository contains my solutions to the exercises in Chapter 5 'SVM' of the book "Hands-On Machine Learning" by Aurélien Géron. The solutions are written in Python using the scikit-learn library.
# SVM Classifiers on Various Datasets

In this repository, I have implemented Support Vector Machine (SVM) classifiers for different datasets as per the requirements of Exercises 8, 9, and 10 from the book "Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow" by Aurélien Géron.

## Exercise 8 - LinearSVC, SVC, and SGDClassifier

### Objective
In Exercise 8, we train three different SVM classifiers (LinearSVC, SVC, and SGDClassifier) on a linearly separable dataset and attempt to make them produce roughly the same model.

### Steps

1. Generate or load a linearly separable dataset.
2. Train a LinearSVC, SVC, and SGDClassifier on the same dataset.
3. Compare the resulting models to see if they produce similar decision boundaries and predictions.

## Exercise 9 - SVM Classifier on MNIST Dataset

### Objective
Exercise 9 involves training an SVM classifier on the MNIST dataset. Since SVM classifiers are binary classifiers, we need to use a one-versus-the-rest (OvR) strategy to classify all 10 digits. The goal is to achieve a high accuracy by tuning hyperparameters using small validation sets.

### Steps

1. Load the MNIST dataset.
2. Split the dataset into training, validation, and test sets.
3. Train 10 binary SVM classifiers (OvR) using the training set and tune their hyperparameters.
4. Combine the binary classifiers to classify all 10 digits.
5. Evaluate the SVM classifier's accuracy on the test set.

## Exercise 10 - SVM Classifier on Wine Dataset

### Objective
Exercise 10 involves training an SVM classifier on the Wine dataset. The Wine dataset contains the chemical analysis of 178 wine samples produced by three different cultivators. We need to train a classification model capable of predicting the cultivator based on the wine's chemical analysis using a one-versus-all approach.

### Steps

1. Load the Wine dataset using `sklearn.datasets.load_wine()`.
2. Split the dataset into training and test sets.
3. Train three binary SVM classifiers (one-versus-all) to classify all three cultivators.
4. Combine the binary classifiers to classify the cultivators.
5. Evaluate the SVM classifier's accuracy on the test set.

## Conclusion

This repository contains the code and results for these three exercises, demonstrating the use of SVM classifiers for different classification tasks on various datasets. You can explore the code and experiment with different hyperparameters and strategies for binary classification and multi-class classification to assess the SVM classifier's performance.
