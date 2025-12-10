# 🏠💰 Real Estate Investment Advisor: Predicting Profitability & Future Value

## 🚀 Project Overview

This is an advanced Machine Learning 🧠 application designed to serve as a **Real Estate Investment Advisor**. The system performs a dual task to empower investors:

1.  **Classification Task:** Determines if a property is a **"Good Investment"** ✅ (High-return prediction).
2.  **Regression Task:** Forecasts the **Estimated Property Price** 📈 after 5 years.

The project emphasizes robust data analysis (EDA), best-practice model training, and seamless deployment using **Streamlit** 📱, with all experiments meticulously tracked via **MLflow** 📊.

---

## 📂 Repository Contents

| File Name | Description |
| :--- | :--- |
| `Real_Estate_Investment_Advisor1.ipynb` | **Core ML Pipeline Notebook** 💻. Contains the complete workflow: Data Cleaning, Feature Engineering, Exploratory Data Analysis (EDA), Model Training (Classification & Regression), and full Evaluation. |
| `best_classification_model.pkl` | **Best Classification Model Weights** 🏆. The final, pre-trained Scikit-learn model (RandomForestClassifier) ready for immediate prediction of **"Good Investment"** status. |
| `Project Title.docx` | **Project Blueprint & Documentation** 📋. Contains the detailed Problem Statement, Business Use Cases, Technical Requirements (MLflow, Streamlit), and Project Objectives. |
| `README.md` | *You are here!* The project documentation. |

---

## 🛠️ Setup and Installation

### 1. Prerequisites
Ensure you have **Python 3.x** installed.

### 2. Environment Setup
Clone the repository and install the necessary data science and MLOps libraries.

```bash
# Clone the repository
git clone [Your-GitHub-Repo-Link]
cd [Your-Project-Folder]

# Install core libraries
pip install pandas scikit-learn xgboost jupyter

# Install MLOps and Deployment libraries
pip install mlflow streamlit
