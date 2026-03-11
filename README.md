# MSCS 634 - Project Deliverable 1
## Advanced Data Mining for Data-Driven Insights and Predictive Modeling

### Student Information
Name: Bishnu Sharma  
Course: MSCS 634  
Deliverable: Project Deliverable 1 – Data Collection, Cleaning, and Exploration  
Date: 11 March 2026

---

## Project Overview
This project focuses on applying data mining techniques to analyze a real-world dataset and extract meaningful insights. The primary objective of Deliverable 1 is to perform data collection, data cleaning, and exploratory data analysis (EDA) to better understand the dataset and prepare it for further predictive modeling in later stages of the project.

The analysis is performed using Python in a Jupyter Notebook environment with libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

---

## Dataset Description
The dataset used in this project is the **Bank Marketing Dataset** obtained from the UCI Machine Learning Repository.

The dataset contains information about direct marketing campaigns conducted by a Portuguese banking institution. The marketing campaigns were based on phone calls, and the goal was to determine whether a client would subscribe to a term deposit.

Dataset characteristics:

- Number of records: **45,211**
- Number of attributes: **17**
- Target variable: **y (subscription to term deposit)**

The dataset includes demographic, financial, and campaign-related information such as:

- Age
- Job type
- Marital status
- Education level
- Account balance
- Housing loan status
- Contact communication type
- Campaign interactions
- Outcome of previous marketing campaigns

---

## Data Cleaning Process
Several preprocessing steps were performed to prepare the dataset for analysis:

1. The dataset was inspected using functions such as `df.head()`, `df.info()`, and `df.describe()` to understand the structure of the data.
2. The dataset was checked for missing values and duplicate records.
3. Some categorical variables contained the value **"unknown"**, representing missing or unclear information.
4. These values were replaced and filled using the **most frequent value (mode)** for each column.

These steps ensured that the dataset was clean and suitable for further analysis.

---

## Exploratory Data Analysis (EDA)
Exploratory Data Analysis was conducted using several visualization techniques to better understand the dataset and identify patterns.

The following visualizations were created:

- Histogram to analyze the **distribution of customer ages**
- Bar chart to observe **subscription outcomes**
- Scatter plot to explore the **relationship between age and account balance**
- Box plot to identify **outliers in account balances**
- Correlation heatmap to examine **relationships between numeric variables**
- Pairplot to visualize **relationships between multiple numeric attributes**

---

## Key Insights
Several important insights were identified during the analysis:

- Most customers fall within the **30–50 age range**.
- The dataset shows a **class imbalance**, with significantly more customers not subscribing to the term deposit.
- Account balances vary widely among customers, with some extreme outliers.
- Most numeric variables show **weak correlations**, indicating that multiple independent factors may influence customer behavior.

---

## Challenges Encountered
One challenge encountered during the project was handling the **"unknown" values** present in several categorical variables. These values represented missing information and required careful handling to avoid losing valuable data.

Another challenge was interpreting relationships between variables since many numeric features showed relatively weak correlations.

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Repository Contents
The repository contains the following files:

- **DataMining_Deliverable1.ipynb** – Jupyter Notebook containing the full data analysis, data cleaning steps, visualizations, and insights.
- **bank-full.csv** – The dataset used for analysis.
- **README.md** – Documentation describing the project, dataset, methodology, and findings.
