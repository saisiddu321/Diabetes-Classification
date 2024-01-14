---
layout: default
# Is title fixed now?
---
# Table of Contents
* * *
### 1. [Introduction and Background](#introduction-and-background)
### 2. [Problem Definition](#problem-definition)
### 3. [Data Collection](#data-collection)
### 4. [Methods](#methods)
### 5. [Results and Discussion](#results-and-discussion)

# Introduction and Background
Diabetes Mellitus more commonly known as Diabetes is a medical condition where the pancreas fails to produce enough 
  insulin and/or the body can not effectively use it. Insulin regulates blood glucose. As a result, the condition causes 
  high levels of glucose in the body. This can lead to damaged nerves, poor blood flow, and vision loss (<a href="https://www.mayoclinic.org/diseases-conditions/diabetes/symptoms-causes/syc-20371444" target="_blank">Diabetes - Symptoms and causes - Mayo Clinic</a>).
  <br><br>
  The dangers of this chronic illness are compounded by its expansive grip across the population. Approximately 1 in ten 
  people in the U.S. have diabetes, which totals to over 37 million people. Over 17 million people were reported to have 
  visited the emergency department and been subsequently diagnosed with diabetes in 2018 (<a href="https://diabetesresearch.org/diabetes-statistics/#:~:text=37.3%20million%20people%2C%20or%2011.3,%2C%20economic%2C%20and%20ethnic%20backgrounds" target="_blank">Diabetes Statistics - DRIF</a>).
  <br><br>
  Early diagnosis is a critical step towards reducing potential damage and beginning remission (<a href="https://www.nhs.uk/conditions/type-2-diabetes/getting-diagnosed/" target="_blank">Source</a>). 
  This not only requires quick and accurate technology to conduct the diagnosis but also identification of trends in patients to 
  determine who may be at high-risk of developing the disease.

# Problem Definition
The aim of this project is to develop an efficient machine learning-based model for the early detection and classification 
of diabetes in patients based on their symptoms.
<br><br>
Timely diagnosis and intervention of diabetes can have a huge impact on a patient's health outcome and have the 
potential to reduce healthcare costs. The recent increase in electronically collected data allows for machine-learning 
models to more accurately diagnose a patient with diabetes (<a href="https://www.nature.com/articles/s41598-020-68771-z" target="_blank">Early detection of type 2 diabetes mellitus using machine 
learning-based prediction models | Scientific Reports</a>). Our goal is to create a predictive model using data with features 
such as Plasma Glucose concentration, Diastolic blood pressure, and many more. 
<br><br>
<i>
Kopitar, Leon, et al. "Early detection of type 2 diabetes mellitus using machine learning-based prediction models." Scientific reports 10.1 (2020): 11981.
</i>

# Data Collection

Our data comes from Kaggle: <a href="https://www.kaggle.com/datasets/mathchi/diabetes-data-set" target="_blank">Diabetes Dataset</a>. 
This specific dataset was sourced from the National Institute of Diabetes and Digestive Kidney Diseases. 
It is worth noting that all the data are from female patients of age 21 or above.
# Methods

We will train several supervised classification models on our dataset and compare their performances, such as logistic regression, 
K-nearest neighbors, SVM's, and neural networks. We will also experiment with different feature reduction techniques, 
such as PCA and LDA, and determine which is more optimal for this specific problem. Finally, we would like to test an 
unstructured EM-based semi-supervised learning model, i.e. GMM, with a self-training approach 
(training a model on the labeled data and iteratively adding the highest confidence guesses from the unlabeled data to 
the training set). The semi-supervised method should have less accuracy (as it uses less information), so we would like 
to gauge the difference in accuracy between the semi-supervised model and the regular supervised models.

# Results and Discussion

The success of this project will have a direct impact on healthcare quality and cost-effectiveness. Our model can serve 
as a tool for healthcare providers, enabling them to efficiently help high-risk individuals. Moreover, it lays the
foundation for future developments in the field of medical diagnostics using machine learning, potentially 
benefiting a wide range of medical conditions beyond diabetes. Overall this will lead to improved patient outcomes, 
reduced hospital admissions, and a more holistic approach to health and wellbeing.

