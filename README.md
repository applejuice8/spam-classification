# Spam Classification

A spam classification model built in `Python` and `Scikit-learn` to filter spam messages.

---

# 2 Distinct Vectorizers

`RandomizedSearchCV` is used for hyperparameter tuning. It found out that the `MLPClassifier` performs best, regardless of being used with `CountVectorizer` or `TF-IDF Vectorizer`.

---

# 2 Best Performing Model + Vectorizer Combinations

## 1. MLPClassifier + CountVectorizer

This model + vectorizer combination is the best performing, getting only 5/1146 wrongly.

## 2. MLPClassifier + TF-IDF Vectorizer

On the other hand, this model + vectorizer combination performs slightly worse than the previous, getting 10/1146 samples wrongly.
