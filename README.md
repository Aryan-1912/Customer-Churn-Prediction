# 📉 Customer Churn Prediction - Telco Dataset

This project focuses on predicting customer churn using the Telco customer dataset. It involves **data exploration (EDA)**, **data preprocessing**, and training **machine learning models** to identify customers likely to discontinue the service.

---

## 📂 Dataset

**Source**: Telco Customer Churn Dataset  
**Features**: Includes customer demographic info, account details, services used, and churn status.  
**Target**: `Churn` (Yes/No)

---

## 🧪 Technologies Used

- 🐍 Python
- 📓 Jupyter Notebook (`.ipynb`)
- 🧮 Pandas, NumPy
- 📊 Matplotlib, Seaborn (for EDA & visualization)
- 🤖 Scikit-learn (for machine learning models)

---

## 📊 Exploratory Data Analysis (EDA)

Performed a detailed EDA to understand:
- Customer demographics (gender, senior citizen, etc.)
- Service usage patterns (internet service, contract type, etc.)
- Financial attributes (monthly charges, total charges)
- Churn correlation with various features

Visual tools: Bar plots, heatmaps, histograms

---

## ⚙️ Model Building

Used supervised learning models to classify churn:
- Data Preprocessing:
  - Handled missing values
  - Encoded categorical variables
  - Feature scaling with `MinMaxScaler`

Evaluation Metrics:
- Accuracy
- Confusion Matrix
- Classification Report

---

## 📈 Results

- Models compared based on accuracy and performance metrics
- Identified key features influencing churn

---

## 📁 File Structure

```bash
├── customer_churn_analysis.ipynb     # Main notebook with EDA and ML code
├── telco_customer_churn.csv          # Dataset (not included here if large)
├── README.md                         # Project documentation
