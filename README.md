# ML-quora-question-pair

Problem Statement

Identify which questions asked on Quora are duplicates of questions that have already been asked.
This could be useful to instantly provide answers to questions that have already been answered.
We are tasked with predicting whether a pair of questions are duplicates or not.****


Source : https://www.kaggle.com/c/quora-question-pairs

Data Overview
Data will be in a file Train.csv
Train.csv contains 5 columns : qid1, qid2, question1, question2, is_duplicate
Size of Train.csv - 60MB
Number of rows in Train.csv = 404,290

Train test split
We did a 70:30 split. ie, we placed 70% of data points for training and the rest 30% for testing.
