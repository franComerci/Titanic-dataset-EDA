# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs a comprehensive Exploratory Data Analysis (EDA) on the famous Titanic dataset. The goal is to uncover patterns and factors that influenced passenger survival rates, such as gender, ticket class, and age.

## 📋 Project Overview

The analysis follows a structured approach:
1.  **Data Loading & Inspection:** Loading the raw data, identifying missing values (`NaN`), and correcting data types.
2.  **Survival Analysis:** Calculating statistical survival rates grouped by:
    * Sex (Male vs. Female)
    * Passenger Class (1st, 2nd, 3rd)
    * Age Groups (Children, Adults, Elderly)
3.  **Visualization:** Generating Bar charts, Violin plots, and Boxplots to visually represent the findings.
4.  **Reporting:** Summarizing actionable insights.

## 🛠️ Technologies Used

* **Python** (3.x)
* **Pandas:** For data cleaning, manipulation, and aggregation.
* **Seaborn & Matplotlib:** For statistical data visualization.
* **Jupyter Notebook:** Interactive environment for running the analysis.

## 📊 Key Findings & Insights

Based on the analysis, the following trends were observed:
* **Women First:** Female passengers had a significantly higher survival probability compared to males.
* **Class Disparity:** First-class passengers were much more likely to survive than those in third class, suggesting socio-economic status played a role in lifeboat access.
* **Age Matters:** Children (ages 0–10) had higher survival rates, whereas the elderly (60+) faced the highest mortality risk.
* **Family Size:** Solo travelers and those with large families had lower survival rates compared to those traveling with small families (1–3 members).

## 📈 Visualizations included
* **Bar Charts:** Comparison of survival rates by Gender and Class.
* **Violin Plots:** Age distribution density across different survival outcomes.
* **Boxplots:** Analysis of Fare prices and Age spread to detect outliers.

## 🚀 How to Run

1.  Clone this repository:
    ```bash
    git clone [https://github.com/franComerci/Titanic-dataset-EDA.git](https://github.com/franComerci/Titanic-dataset-EDA.git)
    ```
2.  Install required libraries:
    ```bash
    pip install pandas seaborn matplotlib jupyter
    ```
3.  Launch the notebook:
    ```bash
    jupyter notebook
    ```

---
*Author: Francisco Comerci*
