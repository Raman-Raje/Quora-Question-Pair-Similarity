# Quora-Question-Pair-Similarity
Objective : To check if give pair of questions is similar or not .

Description: In this problem we have provided two questions with question ID. The task was to determine whether this question are duplicate of one another or not. Data preprocessing and feature engineering was done to get more features. The performance metric used was log-loss.  Tried and tested various ML models to get minimum log-loss.

Observation:
===============
1. Our aim is to get loss less than Random Model which is 0.8872
2. We Used TFIDF vectorizer to get better results.
3. TFIDF vector gave better result in each case as compared to TFIDF-W2V
4. The models trained on TF-IDF are not included here
5. XGBOOST tuning 2 gave the best performance with minimum training of 0.158
