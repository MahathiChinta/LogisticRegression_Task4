# Logistic Regression – Binary Classification (Task 4)

This project focuses on building a **binary classifier using Logistic Regression**. The classification is performed on the **Breast Cancer Wisconsin Dataset**, a well-known dataset used to distinguish between malignant and benign tumor samples.

## Objective

To build and evaluate a logistic regression model for binary classification using Scikit-learn, Pandas, and Matplotlib.

---

## Dataset

- **Name:** Breast Cancer Wisconsin (Diagnostic) Dataset
- **Format:** CSV
- **Source:** [Kaggle] https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data
- **Target Variable:** `diagnosis`  
  - `M` (Malignant → 1)  
  - `B` (Benign → 0)

---

## Steps Performed

1. **Data Loading & Preprocessing**
   - Removed unnecessary columns (`id`, `Unnamed: 32`)
   - Converted diagnosis labels to binary (M → 1, B → 0)
   - Checked for missing values and data imbalance

2. **Train-Test Split**
   - Split data into 80% training and 20% testing

3. **Feature Standardization**
   - Applied `StandardScaler` to normalize feature values

4. **Model Building**
   - Trained Logistic Regression using Scikit-learn

5. **Evaluation Metrics**
   - Accuracy
   - Precision & Recall
   - Confusion Matrix
   - ROC Curve & AUC Score

6. **Threshold Tuning**
   - Adjusted classification threshold to observe its impact

7. **Sigmoid Function**
   - Explained how logistic regression uses the sigmoid function for probability-based predictions

---

## Key Insights

- The dataset was slightly imbalanced but manageable without resampling.
- The logistic regression model achieved high accuracy and AUC, making it suitable for this classification task.
- ROC-AUC helped in visualizing the trade-off between TPR and FPR.
- Threshold tuning showed how prediction probabilities affect classification.

---

## Files Included

- `Task4_LogisticRegression.ipynb` – Main code notebook
- `data.csv` – Dataset file
- `README.md` – Project documentation

---

## Tools Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

Feel free to explore, fork, or suggest improvements to the repository!
