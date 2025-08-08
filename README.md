# Credit Card Fraud Detection

**Notebook:** `creadit_card_fraud.ipynb`  
**Author:** IT21197246 – Abeykoon A.M.Y.V.B

---

## 📖 Overview

This notebook walks through the full pipeline for detecting credit card fraud using the Kaggle [Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud) dataset. The analysis covers:

1. **Data Loading & Inspection**  
2. **Exploratory Data Analysis & Visualization**  
3. **Data Splitting & Feature Scaling**  
4. **Handling Class Imbalance (SMOTE)**  
5. **Training & Hyperparameter Tuning (Logistic Regression)**  
6. **Threshold Analysis**  
7. **Final Evaluation Metrics**  

---

## 🗂 Dataset

- File: `creditcard.csv`  
- Contains 284,807 transactions (rows) with 30 features:  
  - `Time`, `Amount`  
  - `V1`–`V28` (anonymized principal components)  
  - `Class` (0 = non-fraud, 1 = fraud)  

Place `creditcard.csv` in the same directory as the notebook before running.

---

## 🛠️ Requirements

- **Python** 3.8+  
- **Libraries:**  
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
  - scikit-learn  
  - imbalanced-learn  

Install via:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn

```

### Usage

1. Clone this repo

2. Download creditcard.csv and place it alongside the notebook

3. Install dependencies (see above)

4. Launch Jupyter Notebook:

```bash
jupyter notebook creadit_card_fraud.ipynb
```

5. Run all cells to reproduce the analysis, plots, and metrics.


