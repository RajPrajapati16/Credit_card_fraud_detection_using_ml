# 💳 Credit Card Fraud Detection Using Machine Learning

This project focuses on detecting fraudulent credit card transactions using various machine learning algorithms. The dataset is highly imbalanced, presenting a real-world challenge in classification.

---

## 📌 Project Objective

To build a model that accurately detects fraudulent transactions from a given dataset of credit card operations.

---

## 📁 Dataset

- **File**: [`creditcard.csv`](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Rows**: 284,807 transactions
- **Features**: 30 (anonymized due to confidentiality)
- **Target**: `Class` (0 = Legitimate, 1 = Fraud)
- **Source**: European cardholders (September 2013)
- Highly imbalanced data
- The dataset used in this project is available on Kaggle:

  https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

---

## 🚀 Features & Workflow

1. **Data Preprocessing**
   - Handling missing data
   - Normalization / Scaling
   - Balancing classes (undersampling / oversampling)

2. **Model Training**
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - k-Nearest Neighbors

3. **Model Evaluation**
   - Accuracy
   - Confusion Matrix
   - ROC-AUC Curve
   - Precision, Recall, F1 Score

4. **Visualization**
   - Fraud vs Non-Fraud distribution
   - Correlation heatmaps
   - Model comparison

---

## 🧪 How to Use

### 1. Clone this repository
```bash
git clone https://github.com/RajPrajapati16/Credit_card_fraud_detection_using_ml.git
cd Credit_card_fraud_detection_using_ml
```
### 2. Install dependencies
```bash
pip install -r requirements.txt
```
### 3. Run the notebook
```bash
jupyter notebook Credit_card_fraud_detection_using_ml.ipynb
```

---

## 📦 Requirements

Dependencies are listed in [`requirements.txt`](requirements.txt) Install with:

```bash
pip install -r requirements.txt
```

---

## 📊 Results

The notebook displays:

- Confusion matrix

- ROC-AUC score

- Fraud detection performance across models

---

## 🙋‍♂️ Author

Raj Prajapati

---

## 📜 License[(MIT)](LICENSE)

This project is licensed for educational and non-commercial use.
