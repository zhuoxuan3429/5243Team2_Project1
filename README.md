# Credit Card Fraud Analysis

## Project Overview
This project aims to analyze how different transaction factors influence the likelihood of fraud. Analyzing this dataset is essential for understanding transaction trends and identifying key factors associated with fraudulent activity.

Through **data cleaning, exploratory data analysis (EDA), data preprocessing, and feature engineering**, we can uncover patterns in transaction behavior and detect significant trends. EDA allows us to visualize transaction distributions, spot anomalies, and identify relationships between variables, while feature engineering helps refine the dataset for further modeling. 

By focusing on these steps, we aim to extract meaningful insights that can guide future fraud detection efforts and enhance data-driven decision-making.

---

## Dependencies
To run this project, you need the following Python libraries:

- `pandas`
- `numpy`
- `datetime`
- `matplotlib.pyplot`
- `seaborn`
- `sklearn`
- `warnings`
- `category_encoders`
- `scipy.stats`
- `geopandas`

## Dataset Information

All required data is stored in the **`data`** directory. The dataset includes:

### Transaction Data (Six Months)
- `transactions_month_6.csv`
- `transactions_month_7.csv`
- `transactions_month_8.csv`
- `transactions_month_9.csv`
- `transactions_month_10.csv`
- `transactions_month_11.csv`
- `transactions_month_12.csv`

### Fraud Labels
- **`fraud.csv`**: This file contains fraud indicators for transactions. Each transaction can be linked to the fraud data through the corresponding **`trans_id`**.

### How to Run the Code

The main code for analysis is in the Project 1.ipynb notebook.

## Results

The project generates **plots and summary tables** as outputs, which include:

- **Distribution of transactions**
- **Anomalies and fraud trends**
- **Feature importance analysis**
- **Fraud detection insights**

---

## Contributors

- **Zhuoxuan Li (`zl3429`)** – Data Cleaning and Handling Inconsistencies, Report Preparation  
- **Ziyue Gao (`zg2520`)** – Exploratory Data Analysis (EDA), Report Preparation  
- **Dailin Song (`ds4354`)** – Data Preprocessing and Feature Engineering, Report Preparation  
- **Fatih Uysal (`fu2137`)** – Data Preprocessing and Feature Engineering, Report Preparation

## Contact
For any questions or issues, please reach out to the contributors or open an issue in the repository.
