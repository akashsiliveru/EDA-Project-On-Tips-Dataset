# Exploratory Data Analysis: Tip Dataset

> **Project Overview:** A detailed statistical and visual exploration of restaurant transaction data to understand the factors influencing tipping behavior.

## Problem Statement
The goal of this project is to perform **Exploratory Data Analysis (EDA)** on the tip.csv dataset. By analyzing variables such as total bill, day of the week, time of day, and party size, we aim to identify patterns and correlations that determine how much a customer tips.

## Dataset Description
The dataset consists of **244 entries** with **7 features**, providing a snapshot of dining transactions.

| Column | Description | Data Type |
| :--- | :--- | :--- |
| **total_bill** | Total cost of the meal (USD) | Float |
| **tip** | Tip amount given (USD) | Float |
| **sex** | Gender of the bill payer (Male/Female) | Categorical |
| **smoker** | Whether the group included smokers (Yes/No) | Categorical |
| **day** | Day of the week (Thur, Fri, Sat, Sun) | Categorical |
| **time** | Time of day (Lunch/Dinner) | Categorical |
| **size** | Number of people in the party | Integer |

## Steps Performed

1.  **Data Loading & Inspection**: Importing libraries and loading the CSV file via Pandas.
2.  **Statistical Profiling**: 
    * Calculated central tendencies (Mean, Median).
    * Measured **Skewness** and **Kurtosis** to determine the shape of the data distribution.
3.  **Univariate Analysis**: Examining the spread of total_bill and tip using distribution plots.
4.  **Bivariate/Multivariate Analysis**: 
    * Relationship between total_bill and tip.
    * Impact of categorical variables (day, sex, time) on tipping.
5.  **Outlier Detection**: Using Box Plots to identify extreme values in spending and tipping.

##  Visualizations
To derive insights, the following visualizations were implemented:
*  **Histograms & KDE**: To check the density and skewness of the bill amounts.
*  **Box Plots**: To compare bill distributions across different days and identify outliers.
*  **Scatter Plots**: To observe the correlation between the bill amount and the tip.
*  **Count Plots**: To visualize customer traffic based on the day of the week and meal time.

##  Key Insights
* **Spending Habits**: The average bill is approximately **$19.78**, with a distribution that is slightly right-skewed.
* **Peak Traffic**: **Saturday** is the busiest day, followed by Sunday, suggesting higher revenue potential during weekends.
* **Tipping Correlation**: There is a visible positive correlation; as the total_bill increases, the tip amount generally increases.
* **Time of Day**: Dinner time accounts for a larger portion of the dataset compared to lunch, often resulting in higher total bills.
* 
## Tools Used
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Seaborn-444876?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-013243?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" />
</p>

- **Python**: Primary programming language.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib & Seaborn**: Data visualization.
- **SciPy**: Statistical analysis (Skewness & Kurtosis).

### Usage
1. Clone the repository.
2. Ensure tip.csv is in the project folder.
3. Open EDA On Tip dataset.ipynb in Jupyter Notebook or VS Code to view the full analysis.
