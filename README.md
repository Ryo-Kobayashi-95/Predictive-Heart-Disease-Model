# Report: Predicting Heart Disease Using ML Algorithms

Published: Nov 12, 2022

Author: Ryo Kobayashi

<br/>

## *Abstract:*
This report focuses on predicting heart disease presence using a dataset with critical attributes. Employing preliminary exploratory data analysis, the attributes of age, maximum heart rate (thalach), and exercise-induced ST depression (oldpeak) emerge as pertinent for subsequent analysis. Leveraging a K-Nearest Neighbour (KNN) classification model, the study aims to ascertain the predictive capacity of these identified predictors concerning heart disease incidence. Impressively, the model attains an accuracy of 72%, aligning with established industry benchmarks. While the achieved accuracy stands as moderate, it furnishes valuable insights into the realm of heart disease risk factors, with conceivable implications for advancing early diagnosis and patient care. 

## *Target Audience:*
This project is tailored for individuals with a vested interest in exploring the potent fusion of machine learning within the healthcare domain. It caters to those who seek insights into the probability of heart disease occurrence based on specific attributes. *It's important to note that while the project provides valuable insights, its practical application is not advisable due to its experimental nature.*

## *Rationale for the Project:*
In light of the growing potency of machine learning and its expanding role within the healthcare domain, embarking on the creation of such a model presents a significant learning opportunity to grasp the intricate mechanics underpinning healthcare-oriented models. This initiative stands as an excellent pathway to delve into the operational dynamics of healthcare models.


## *Stages in Model Creation:*

### 1. Initial Exploratory Data Analysis:
   - Data reading and preprocessing
   - Division of dataset into training and testing subsets
   - Visual exploration of training data to identify suitable attributes for model development

![image](https://github.com/Ryo-Kobayashi-95/Report-on-predictive-heart-disease-model/assets/115038173/e9a99999-3e32-4ccc-8ce8-8dff05e41728)

### 2. Model Construction and Accuracy Assessment:
   - Construction of the KNN model with consideration for varying K-Neighbours values
   - Optimal K-Neighbours selection (found to be 9)
   - Evaluation of model performance using the confusion matrix
   - Analysis of attribute correlations to gauge the efficacy of chosen attributes

![image](https://github.com/Ryo-Kobayashi-95/Report-on-predictive-heart-disease-model/assets/115038173/2865b565-14fa-4d3b-84b9-0366c0936391)

![image](https://github.com/Ryo-Kobayashi-95/Report-on-predictive-heart-disease-model/assets/115038173/109ce6f6-8e0f-4c01-a27d-5b9d79136a2a)

## *Source*
Dataset retrieved from: https://archive.ics.uci.edu/dataset/45/heart+disease




