# Machine-Learning-HW

## Table of Contents

1. [Section 1 (Resampling With Imbalanced Learn and Predicting Loan Risk](#Section-1)
2. [Section 2 (Ensemble Classifiers to Predict Loan Risk)](#Section-2)

## Section 1

**Goal:** Use different oversampling/undersampling methods and linear regression to predict loan risk classification (high = 1 vs. low = 0)

**Linear Regression without Resampling - Classification Report**
---
![Linear Regression without Resampling](Images/LR.jpg)

**Random Oversampling - Classification Report**
---
![Linear Regression with Random Oversampling](Images/Random.jpg)

**SMOTE Oversampling - Classification Report**
---
![Linear Regression with SMOTE Oversampling](Images/SMOTE.jpg)

**ClusterCentroid Undersampling - Classification Report**
---
![Linear Regression with ClusterCentroid Undersampling](Images/CC.jpg)

**SMOTEENN Combination Sampling - Classification Report**
---
![Linear Regression with SMOTEENN Combination Sampling](Images/SMOTEENN.jpg)

**Question 1:** Which model had the best balanced accuracy score?

- **Answer:** The Random, SMOTE, & SMOTEENN models have the best accuracy scores with equal accuracy scores of 99.3%

    - No resampling balanced accuracy score: 0.9889
    - Random resampling balanced accuracy score: 0.9934
    - SMOTE resampling balanced accuracy score: 0.9934
    - ClusterCentroid resampling balanced accuracy score: 0.9929
    - SMOTEENN resampling balanced accuracy score: 0.9934

**Question 2:** Which model had the best recall score?

- **Answer:** All models have consistent recall scores of 99%

**Question 3:** Which model had the best geometric mean score?

- **Answer:** All models have consistent geometric mean scores of 99%


## Section 2

**Goal:** Use different ensemble classifier methods to predict loan risk classification (high = 1 vs. low = 0)

**Balanced Random Forest - Classification Report**
---
![Balanced Random Forest](Images/BRF.jpg)

**Easy Ensemble Classifier - Classification Report**
---
![Easy Ensemble Classifier](Images/EEC.jpg)

**Question 1:** Which model had the best balanced accuracy score?

- **Answer**: The Easy Ensemble Classifier has the best balanced accuracy score of .93

**Question 2:** Which model had the best recall score?

- **Answer**: The Easy Ensemble Classifier has the best recall score of .94

**Question 3:** Which model had the best geometric mean score?

- **Answer**: The Easy Ensemble Classifier has the best geometric mean score of .93

**Question 4:** What are the top three features?

- **Answer**: The Top Three Features are: 

    - total_rec_prncp (~8%)
    - total_pymnt_inv (~6%)
    - total_rec_int (~6%)
