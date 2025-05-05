# Understanding-Naive-Bayes-with-Scikit-learn
This repository provides a comprehensive guide to understanding and implementing Naive Bayes algorithms using Scikit-learn. The examples cover three main types of Naive Bayes classifiers—GaussianNB, MultinomialNB, and BernoulliNB—demonstrating their application, performance, and hyperparameter tuning.

This repository is designed to give you an in-depth understanding of the Naive Bayes algorithm in Scikit-learn, which is a powerful classification algorithm based on Bayes' Theorem. It includes the following:

* **Gaussian Naive Bayes (GaussianNB):** Used when the features follow a Gaussian (normal) distribution.

* **Multinomial Naive Bayes (MultinomialNB):** Works well for count-based data such as word counts in text classification.

* **Bernoulli Naive Bayes (BernoulliNB):** Ideal for binary/boolean features (e.g., presence or absence of a feature).

You will find step-by-step code implementations, first without using the make_pipeline utility to demonstrate how preprocessing and modeling can be handled separately. Then, the same tasks are implemented using make_pipeline to streamline preprocessing and modeling into a single, more efficient pipeline.

The repository also compares different model variants, their configurations, and performance when using various hyperparameters, providing insights into how to fine-tune models for better accuracy.
