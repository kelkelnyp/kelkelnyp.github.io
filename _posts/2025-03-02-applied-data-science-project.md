---
layout: post
author: Kelly 
title: "Applied Data Science Project Documentation"
categories: ITD214
---
## Project Background
Hotels in the USA have collected quantitative data (reviews.rating) and qualitative data (reviews.text) over a period of 15 years 5 months from 1 Sep 2003 to 30 Jan 2019
Would like to see what actionable insights can be derived from the collected data 


Business Goal
To help USA hotels to improve their service and with a small budget , we can look into reviews leading to positive results to get started
  
## Work Accomplished
Predict whether a review is a positive or negative sentiment (sentiment analysis)

### Data Preparation
Outline 
- Clean Data
- Conduct preprocessing steps
- Prepare word representation
- Accuracy of review rating


### Modelling
DecisionTreeClassifier /
bow_features /
tfidf_features /
tensorflow 

### Evaluation
Enhancing Guest Satisfaction with Sentiment Analysis:
By using the selected model to predict new review, we could test the accuracy of the text rating been provided earlier in the data we have chosen for this project.
What is the deciding facts to choose TF-IDF model over BoW model & Tensor flow ? - Final conclusion - the results in TF-IDF model outperforms 2 others models in predicting hotel review sentiment. Its higher accuracy, precision, recall, and F1-scores suggest better performance. 
![image](https://github.com/user-attachments/assets/a2c8783e-94a3-4d61-807b-2cddecea6ddf)

## Recommendation and Analysis
Explain the analysis and recommendations
Analysis: The TF-IDF model before SMOTE is applied. It reveals that the 'Good' reviews are the majority class (around 77%), while 'Bad' reviews are the minority (around 23%). This analysis helped us understand the positive and negative aspects of guest experiences.
Recommendations:
Proactive Service Recovery: Implement a system to identify and address negative reviews in real-time, offering solutions and demonstrating a commitment to guest satisfaction.
Staff Training: Train staff to address common guest concerns example room cleanliness and hotel staff service.It provide exceptional service in areas identified as needing improvement.
Personalized Experiences: Leverage sentiment analysis to personalize guest interactions, offering tailored recommendations and amenities based on their preferences - Use a customer journey map template to help create each persona.


## AI Ethics
Ensure data meet privacy regulation. General Data Protection Regulation (GDPR) and the Personal Data Protection Act (PDPA) 
The PDPA recognises both the need to protect individuals’ personal dataand the need of organisations to collect, use or disclose personal data for legitimate and reasonable purposes.
● Consent Obligation
● Purpose Limitation Obligation
● Protection Obligation
● Retention Limitation Obligation
● Transfer Limitation Obligation
● Accuracy Obligation


## Source Codes and Datasets
https://github.com/kelkelnyp/itd214.proj

