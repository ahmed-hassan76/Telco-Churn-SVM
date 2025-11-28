# Telco-Churn-SVM
A continuation of the repo Churn Flow, but we use an SVM to compare against the Markov Model

This repository contains the full implementation, analysis, and reporting for predicting customer churn using two distinct methodologies:  
1. A **Support Vector Machine (SVM)** classifier implemented from scratch in Python  
2. A **Markov Model** built to analyze customer state transitions  

The project explores how traditional probabilistic models compare to modern machine learning techniques in predicting churn within a Telco customer dataset.

---

## 🚀 Project Overview

Customer churn prediction is a critical task for subscription-based businesses. This project focuses on identifying customers at risk of leaving by analyzing key behavioral and contractual attributes.

We compare two approaches:

### **1️⃣ Markov Model**
- Computes transition probabilities between customer states  
- Identifies the most likely next state for each segment  
- Reveals structural trends such as:
  - High churn probabilities among Month-to-Month customers
  - Higher loyalty for customers with longer tenures or annual contracts

### **2️⃣ Support Vector Machine (SVM)**
- Implemented manually without using scikit-learn's SVM
- Uses encoded and standardized numerical/categorical features
- Predicts churn at the individual customer level
- Achieved **~81% accuracy**, outperforming the Markov Model in precision

---

## 📊 Key Results

### **Markov Model**
- Provided transition probability insights.
- “Churned” was consistently among the top 3 predicted states.
- Identified structural customer behavior patterns but lacked precise prediction.

### **SVM Model**
- Accuracy: **~81%**
- Successfully handled class imbalance with preprocessing.
- Outperformed the Markov Model for instance-level classification.

---

## 🛠️ Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Custom SVM implementation  
- Markov transition probability matrix  
- Jupyter Notebook  

---

## 📈 Visualizations
Includes:
- Correlation heatmaps  
- Churn distribution plots  
- Markov transition diagrams  
- SVM prediction comparisons  

---

## 📑 Final Report
A full academic-style report discussing:
- Problem formulation  
- Dataset preprocessing  
- Attribute importance  
- Methodologies used  
- SVM and Markov results  
- Comparative analysis  
- Final conclusions  

---

## 👤 **Author**
**Ahmed Hassan**
Faculty of Business Informatics
German University in Cairo  




