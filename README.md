# **Credit Card Fraud Detection - Exploratory Data Analysis (EDA)**

![Project Banner](https://img.shields.io/badge/Python-EDA-blue?logo=python)  
> Exploring credit card transaction patterns to identify fraudulent activities using Python.

## **Table of Contents**
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Objectives](#project-objectives)
- [EDA Highlights](#eda-highlights)
- [Technologies Used](#technologies-used)
- [How to Use](#how-to-use)
- [Key Visualizations](#key-visualizations)
- [Acknowledgments](#acknowledgments)

---

## **Introduction**
Credit card fraud is a significant concern, leading to financial losses and reduced consumer trust. This project focuses on performing Exploratory Data Analysis (EDA) to uncover patterns and anomalies in credit card transaction data, distinguishing fraudulent transactions from legitimate ones.

---

## **Dataset**
**Dataset Name:** Credit Card Fraud Detection Dataset  
**Source:** [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
- Contains 284,807 rows and 31 columns.
- Features include anonymized variables (`V1, V2, ..., V28`), `Amount`, and a `Class` label (0 = Legitimate, 1 = Fraudulent).

---

## **Project Objectives**
1. Understand the structure and key attributes of the dataset.
2. Identify patterns and anomalies in transactions.
3. Visualize correlations between features to gain actionable insights.
4. Highlight distinctions between fraudulent and legitimate transactions.

---

## **EDA Highlights**
- **Fraud Statistics:** Fraudulent transactions account for only 0.17% of the dataset.  
- **Amount Distribution:** The histogram shows most transactions are low-value, with outliers on the higher end.  
- **Correlation Analysis:** A heatmap reveals relationships among numerical features, providing insight into transaction patterns.  
- **Visualizations:**  
  - Bar chart comparing counts of legitimate and fraudulent transactions.  
  - Histogram of transaction amounts.  
  - Correlation heatmap of numerical features.

---

## **Technologies Used**
- **Programming Language:** Python  
- **Libraries:**  
  - [Pandas](https://pandas.pydata.org/) for data manipulation.  
  - [Matplotlib](https://matplotlib.org/) and [Seaborn](https://seaborn.pydata.org/) for visualizations.

---

## **How to Use**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-eda.git
   cd credit-card-fraud-eda.git
