# Credit Card Fraud Detection

**Author:** IT21197246 – Abeykoon A.M.Y.V.B

---

## Table of Contents

1. [Project Overview](#project-overview)  
2. [Dataset](#dataset)  
3. [Dependencies](#dependencies)  
4. [Notebook Structure](#notebook-structure)  
5. [Usage](#usage)  
6. [Results & Insights](#results--insights)  
7. [License](#license)

---

## Project Overview

This notebook walks through an end-to-end machine learning pipeline to detect fraudulent credit-card transactions. It covers:

- Data loading and exploratory analysis  
- Handling class imbalance with SMOTE  
- Feature scaling  
- Training and hyperparameter tuning of a Logistic Regression model  
- Threshold analysis and model evaluation  
- Visualization of performance metrics (confusion matrix, ROC and precision–recall curves)

---

## Dataset

We use the publicly available [Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud) dataset, which contains transactions made by European cardholders in September 2013. The data has already been PCA-transformed for privacy; features `V1`–`V28` are principal components, plus:

- **Time**: seconds elapsed between this transaction and the first one in the dataset  
- **Amount**: transaction amount in euros  
- **Class**: target label (0 = genuine, 1 = fraud)

Place the `creditcard.csv` file in the same directory as this notebook before running.

---
# Credit Card Fraud Detection

**Author:** IT21197246 – Abeykoon A.M.Y.V.B

---

## Table of Contents

1. [Project Overview](#project-overview)  
2. [Dataset](#dataset)  
3. [Dependencies](#dependencies)  
4. [Notebook Structure](#notebook-structure)  
5. [Usage](#usage)  
6. [Results & Insights](#results--insights)  
7. [License](#license)

---

## Project Overview

This notebook walks through an end-to-end machine learning pipeline to detect fraudulent credit-card transactions. It covers:

- Data loading and exploratory analysis  
- Handling class imbalance with SMOTE  
- Feature scaling  
- Training and hyperparameter tuning of a Logistic Regression model  
- Threshold analysis and model evaluation  
- Visualization of performance metrics (confusion matrix, ROC and precision–recall curves)

---

## Dataset

We use the publicly available [Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud) dataset, which contains transactions made by European cardholders in September 2013. The data has already been PCA-transformed for privacy; features `V1`–`V28` are principal components, plus:

- **Time**: seconds elapsed between this transaction and the first one in the dataset  
- **Amount**: transaction amount in euros  
- **Class**: target label (0 = genuine, 1 = fraud)

Place the `creditcard.csv` file in the same directory as this notebook before running.

---

## Dependencies

This notebook was developed with Python 3.x and tested against the following packages:

- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `scikit-learn`  
- `imbalanced-learn`
  
