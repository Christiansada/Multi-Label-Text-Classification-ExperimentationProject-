# Multi-Label Text Classification Project

This project aims to perform multi-label text classification using various machine learning classifiers. The dataset consists of text documents labeled with multiple categories, and the goal is to predict the categories for new, unseen documents accurately.

## Dataset

The dataset used in this project contains text documents with associated labels. Each document can belong to multiple categories, making it a multi-label classification task. The dataset has been preprocessed and split into training and test sets.

## Approach

### Part 1: Preprocessing and Exploration

In this part, the dataset is loaded and preprocessed. Text preprocessing techniques such as lowercasing, removing punctuation, and tokenization are applied. Additionally, exploratory data analysis (EDA) is performed to gain insights into the distribution of labels and document lengths.

### Part 2: Baseline Model

A baseline model is built using a simple bag-of-words approach with TF-IDF vectorization and a logistic regression classifier. This model serves as a benchmark for evaluating the performance of more advanced classifiers.

### Part 3: Classifier Evaluation

In this part, several classifiers are evaluated using TF-IDF representations of character n-grams of varying lengths (from 7 to 10). The classifiers include Bagging, AdaBoost, Multinomial Naive Bayes, Random Forest, Logistic Regression, and Linear SVC, all wrapped within a OneVsRestClassifier for multi-label classification. The performance of each classifier is evaluated using metrics such as accuracy, precision, recall, and F1-score.

## Results

The results of the classifier evaluation are presented, showing the performance of each classifier across different character n-gram lengths. This allows for comparison and selection of the most suitable classifier for the multi-label text classification task.

## Conclusion

This project provides insights into the effectiveness of different classifiers for multi-label text classification tasks. By comparing the performance of various classifiers and exploring different text representations, it aims to help in selecting the best approach for similar tasks in the future.

