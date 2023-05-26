# Naive-Bayes-Email-Spam-Filter

## Problem Statement

Build a machine learning framework using Naive Bayes classifier to design email spam filter.

## Dataset

[DBWorld e-mails Data Set](https://archive.ics.uci.edu/ml/datasets/dbworld+e-mails)

This dataset was created from 64 emails collected from the DBWorld mailing list. There are two datasets, dbworld_bodies_stemmed and dbworld_subjects_stemmed corresponding to the email body and email subject respectively. The data is currently represented as a binary stemmed bag-of-words and requires no additional NLP.

## Results

- The model/classifier is **trained using 80% data of the given dataset and the remaining 20% is used for testing.**  
  - The **classifier developed from the scratch** performed prediction on both the given datasets and followings are their f_measure. 
    - "dbworld_subjects_stemmed.csv" ----->   F_Measure =  0.9090909090909091
    - "dbworld_bodies_stemmed.csv" ----->   F_Measure =  0.888888888888889

- For both the given datasets, the same model is used for **scikit_learn MultinomialNB** for comparing the efficacy of the algorithm designed from the scratch.
  - The **sci-kit learn classifier** performed prediction on both the given datasets and followings are their f_measure. 
    - "dbworld_subjects_stemmed.csv" ----->   F_Measure =  0.9090909090909091
    - "dbworld_bodies_stemmed.csv" ----->   F_Measure =  0.888888888888889
