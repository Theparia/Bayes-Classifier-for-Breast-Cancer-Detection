# Bayes-Classifier-for-Breast-Cancer-Detection
This repository contains code for breast cancer detection using Naive Bayes classifiers. Three different Naive Bayes classifiers are implemented: `Gaussian Naive Bayes` Classifier from scratch, `Gaussian Naive Bayes` Classifier using the `scikit-learn` library, and `Gaussian Optimal Bayes` Classifier from scratch.

## Gaussian Naive Bayes
Gaussian Naive Bayes (GNB) is a probabilistic classifier ideal for Gaussian-distributed data. It assumes **feature independence**, making it efficient for many tasks, but less suitable for correlated features.

## Gaussian Optimal Bayes
Gaussian Optimal Bayes (GOB) extends GNB by considering **feature covariance**, accommodating correlated features. It uses multidimensional Gaussian distributions, making it more flexible in capturing complex relationships. GOB is suitable when features are not independent but is computationally more demanding than GNB.
