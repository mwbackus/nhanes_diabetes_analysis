## Overview

This project explores the prediction of diabetes status using data from the **National Health and Nutrition Examination Survey (NHANES)**. The dataset includes information from 2009-2012 and contains various health and demographic variables. The primary objective is to study risk factors associated with diabetes and compare the predictive performance of multiple supervised machine learning algorithms.

### Machine Learning Models
I employed the following machine learning classifiers to predict diabetes status:
1. **Decision Tree Classifier**
2. **K-Nearest Neighbors (KNN)**
3. **Naive Bayes Classifier**
4. **Logistic Regression Classifier**

### Key Results
- **Decision Tree Classifier**: Accuracy: ~91.25%
- **KNN Classifier**: Accuracy: ~90.54%
- **Naive Bayes Classifier**: Accuracy: ~90.60%
- **Logistic Regression Classifier**: Accuracy: **91.66%**

---

## Project Objectives

1. Analyze diabetes-related risk factors.
2. Define training and test datasets (80/20 split).
3. Train and compare supervised learning models.
4. Evaluate the models using metrics such as accuracy, confusion matrix, and sensitivity to imbalanced data.

---

## Dataset

The NHANES dataset includes 7,555 rows (observations) and 76 variables related to health and lifestyle markers. This project focuses on:
- `Age`
- `Gender`
- `BMI` (Body Mass Index)
- `Diabetes` (binary response variable)
- `HHIncome` (Household Income)
- `PhysActive` (Physical Activity)

> Full details about NHANES data are available on the [NHANES CDC website](https://wwwn.cdc.gov/nchs/nhanes/Default.aspx).

---

## Installation

To clone this project repository, run the following command in your terminal:

```bash
git clone https://github.com/yourusername/stat540_project3.git

You can then explore the data under /data or execute the R code in /code
