# 📊 Bank Loan Case Study – Data Analysis Project

## 🧠 Project Overview

This project is a comprehensive data analysis case study focused on improving **loan approval decisions** for a financial institution. The company faces challenges in evaluating applicants with **incomplete or no credit history**, leading to two key problems:

- **False rejections** of creditworthy applicants.
- **Approvals of high-risk individuals** who later default.

Using **Microsoft Excel**, this project applies a step-by-step data analysis pipeline to extract actionable insights that can support smarter, data-driven underwriting decisions.

---

## 🎯 Objectives

- Detect and treat missing data and outliers.
- Analyze class imbalance in the target variable.
- Identify key variables influencing loan default.
- Explore feature correlations for improved modeling.
- Prepare the dataset for machine learning.

---

## 🧰 Tools & Technologies

- **Microsoft Excel**
  - Functions: `IF`, `ISBLANK`, `AVERAGE`, `MEDIAN`, `MODE`, `CORREL`
  - Features: Pivot Tables, Conditional Formatting, Charts, Box Plots

---

## 🗂️ Dataset

- **Source**: Provided internally as `application_data_1.xlsx`
- **Records**: ~50,000 loan applicants
- **Key Features**:
  - Demographics (age, gender, family size)
  - Financial info (income, credit, annuity)
  - Employment and registration dates
  - Loan repayment behavior (`TARGET` variable)

---

## 📌 Key Tasks & Highlights

### ✅ 1. Missing Data Treatment
- Identified high-missing columns using `ISBLANK()`.
- Imputed moderate-missing values using statistical methods.
- Dropped variables with excessive missingness.

### ✅ 2. Outlier Detection
- Used IQR-based box plots to identify and flag extreme values.
- Focused on variables like `AMT_INCOME_TOTAL`, `CNT_CHILDREN`, `DAYS_EMPLOYED`.

### ✅ 3. Target Variable Imbalance
- Found significant imbalance:
  - 92% non-defaulters
  - 8% defaulters
- Suggested SMOTE or class weighting for modeling.

### ✅ 4. Univariate & Bivariate Analysis
- Identified high-risk groups: unemployed, low education, younger applicants.
- Found that applicants with academic degrees or government jobs had the lowest default rates.

### ✅ 5. Correlation Analysis
- Removed highly correlated features (e.g., `AMT_CREDIT` vs `AMT_GOODS_PRICE`).
- Retained key predictors for future ML usage.

---

## 📈 Business Outcomes

- Cleaned and structured data, **ready for ML model training**.
- Improved **credit risk segmentation**.
- Actionable insights for better **customer targeting** and **loan approval policies**.
- Foundation for building **predictive models** in Python, Power BI, or Excel.

---

## 🚀 Next Steps

- Develop logistic regression or decision tree model using this dataset.
- Apply SMOTE or similar technique to address class imbalance.
- Deploy insights into loan approval workflows to reduce default rates.

---

## 📫 Contact

Created by: **[Mrityunjay]**  
For inquiries or collaboration: [📧](m9919614@gmail.com)[m9919614@gmail.com]                            
LinkedIn: [Mrityunjay](https://www.linkedin.com/in/mrityunjay-gupta-663290263/) [https://www.linkedin.com/in/mrityunjay-gupta-663290263/]

---

## 📎 Files Included

- `application_data_1.xlsx` – Raw dataset
- `Bank Loan Case Study.pdf` – Detailed report
- `Presentation.pdf` – Visual summary of the analysis
  
