
---

# Banking Churn Predictor

This repository contains a data science project aimed at predicting customer churn in the banking sector. The project involves data processing, exploratory data analysis (EDA), feature engineering, and model training to identify key factors influencing customer churn and provide actionable insights.

## Table of Contents

1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Project Structure](#project-structure)
4. [Key Features and Methods](#key-features-and-methods)
5. [Usage](#usage)
6. [Technologies Used](#technologies-used)
7. [Results](#results)
8. [Future Improvements](#future-improvements)

## Overview

Customer churn is a critical issue for banks, as it directly impacts profitability. This project focuses on analyzing various factors such as customer demographics, account information, and transaction behaviors to predict the likelihood of a customer leaving the bank. By understanding these factors, banks can develop strategies to retain valuable customers.

## Dataset

The dataset contains information about bank customers and includes the following key columns:

1. **RowNumber:** Unique identifier for each record and does not contribute directly to the analysis.
2. **CustomerId:** Used to track and differentiate individual customers within the dataset.
3. **Surname:** Provides information about the family name of each customer.
4. **CreditScore:** Numerical value that assesses the creditworthiness of an individual based on their credit history and financial behavior.
5. **Geography:** Provides information about the customers' geographic distribution, allowing for analysis based on regional or national factors.
6. **Gender:** Categorizes customers as either male or female, enabling gender-based analysis if relevant to the churn prediction.
7. **Age:** Represents the customer's age in years and can be used to analyze age-related patterns and behaviors.
8. **Tenure:** Typically represents the number of years or months the customer has been associated with the bank.
9. **Balance:** Reflects the amount of money in the customer's bank account at a specific point in time.
10. **NumOfProducts:** Number of products the customer has with the bank, such as savings accounts, loans, credit cards, etc.
11. **HasCrCard:** Binary variable with a value of 1 if the customer possesses a credit card and 0 otherwise.
12. **IsActiveMember:** Binary variable indicating whether the customer is an active member (1) or not (0) within the bank.
13. **EstimatedSalary:** Provides an approximation of the customer's income level, which can be relevant for analyzing churn behavior.
14. **Exited:** Indicates whether a customer has churned (1) or not (0) from the bank. It is the variable we aim to predict using the other features.

## Project Structure

```
Banking_Churn_Analysis/
│
├── data/               # Raw and processed datasets
├── notebooks/          # Jupyter notebooks
│   ├── 1_data_processing.ipynb
│   ├── 2_eda.ipynb
│   ├── 3_feature_engineering.ipynb
│   ├── 4_model_building.ipynb
```

## Key Features and Methods

1. **Data Processing:**
   - Handled missing values and inconsistencies in the dataset.
   - Encoded categorical variables and normalized numerical data.

2. **Exploratory Data Analysis (EDA):**
   - Investigated distributions, correlations, and key patterns in the data.
   - Identified key factors influencing customer churn.

3. **Feature Engineering:**
   - Created new features based on customer behaviors and demographics.
   - Selected features based on importance scores.

4. **Model Training:**
   - Trained machine learning models (e.g., logistic regression, random forest).
   - Evaluated performance using accuracy, precision, recall, and F1-score.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Santheeppa/Banking-Churn-Predictor.git
   cd Banking-Churn-Predictor
   ```
2. Run Jupyter notebooks for data processing, analysis, and training:
   ```bash
   jupyter notebook
   ```

## Technologies Used

- **Python Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn
- **Jupyter Notebook:** For interactive data exploration and analysis

---
Hey there! 😊


I did this project after referring to many projects from Kaggle and GitHub. I learned numerous new methods through them and applied many of them in this project. There is still more to learn, and I am committed to doing my best in future projects as well.Thanks so much for your support and understanding!

Cheers, [Santheeppa]

---

Feel free to tweak it if needed! 


Cheers, [Santheeppa]

---

Feel free to contribute by submitting issues or pull requests.

---

