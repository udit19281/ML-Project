# Personality Prediction using Myers Briggs Type Indicator

by **Dolly Sidar**, **Vidhi Sharma**, and **Udit Bhati**, Machine Learning (CSE343/ECE343) under the guidance of **Dr. Jainendra Shukla** from **Indraprastha Institute of Information Technology, Delhi**.

![cover](https://user-images.githubusercontent.com/66681287/154308670-adfc4868-209e-418f-a7f9-d40b0227a15d.png)

## Motivation
In today’s era, personality is one of the heavily researched and fascinating topics in psychology. Personality recognition of users is widely used in research domains like recommendation systems and human-robot interaction. Traditional recommendation systems come across problems like lack of data about the preferences of the user, free-riders problem, and the data sparsity problem. The identified user personality traits help understand users’ preferences. MBTI’s test-retest reliability hovers around a 0.5 error rate. On retest, people come out with 3–4 type preferences 75–90% of the time. Our methodology can assist with more accuracy than currently existing tests, allowing users to rely on their outcomes. Personality classification based on digital data has proved to be a more efficient alternative to traditional psychological tests.

## Introduction
With over 3.5 million assessments conducted each year, MBTI is the most widely used personality indicator globally. The Myers Briggs Type Indicator (MBTI) is a personality type system that divides everyone into 16 distinct personalities based on four dimensions, namely: Introversion (I) — Extroversion (E), Intuition (N) — Sensing (S), Thinking (T) — Feeling (F), Judging (J) — Perceiving (P). MBTI predicted personality traits retain essential properties of the traditional personality characteristics. Researchers widely use machine learning and deep learning algorithms to predict personality and psychological traits from digital records.

We’re developing an MBTI personality classifier that uses machine learning models to predict a person’s personality based on the 50 recent social media posts per user as input. We find correlations between a person’s MBTI personality type and writing style. The classifier also demonstrates the validity of the MBTI test. We have used a decent amount of mined personality annotated data from social media. Furthermore, our model would run on more data than that provided in a conventional personality test, which serves as a confirmation system and helps people rely more on the results.

## Dataset
Download dataset from [Myers-Briggs Personality Type Dataset.](https://www.kaggle.com/datasnaek/mbti-type)

## Models
* Logistic Regression
* Naive Bayes 
* Random Forest Classifier
* K-Nearest Neighbor (KNN)
* SGD Classifier
* Support Vector Machines (SVM)

## How to Run ?
### Install dependencies
pip install -r requirements.txt

### Run
python ml_group15_project.py

## Contact
For further queries feel free to reach out to following contributors.
* Dolly Sidar (dolly19304@iiitd.ac.in)
* Udit Bhati (udit19281@iiitd.ac.in)
* Vidhi Sharma (vidhi19286@iiitd.ac.in)

## Final Report
[Report.pdf](https://github.com/dolly19/ML-Project/files/8081709/Report.pdf)


