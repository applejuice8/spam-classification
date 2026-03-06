# Spam Classification

A spam classification model built in `Python` and `Scikit-learn` to filter spam messages.

Data from [Kaggle Spam Email Dataset](https://www.kaggle.com/datasets/jackksoncsie/spam-email-dataset)

---

# 2 Distinct Vectorizers

`RandomizedSearchCV` is used for hyperparameter tuning. It found out that the `MLPClassifier` performs best, regardless of being used with `CountVectorizer` or `TF-IDF Vectorizer`.

---

# Best Performing Model With Each Vectorizer

## 1. CountVectorizer + MLPClassifier

Accuracy: 0.9747292418772563

Confusion matrix:
 [[865   7]
 [  4 270]]

## 2. TF-IDF Vectorizer + MLPClassifier

Score: 0.9712230215827338

Confusion matrix:
 [[864   8]
 [  4 270]]
