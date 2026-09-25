<div align="center">

# Customer Churn Analytics:
 
[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?logo=pandas)](https://pandas.pydata.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
 
</div>

---
 
## 📌 Table of Contents
- [Overview](#-overview)
- [Business Questions](#-business-questions)
- [Dataset](#-dataset)
- [Tech Stack](#-tech-stack)
- [Analysis Workflow](#-analysis-workflow)
- [Key Insights](#-key-insights)
- [Contact](#-contact)
---
 
## 🔍 Overview
 
Customer churn is a key concern for subscription-based businesses, where retaining existing customers is often more valuable than acquiring new ones. This project explores a simulated dataset of 20,000 customers to identify which factors — such as contract type, support calls, and tenure — are most associated with churn, using exploratory data analysis and segmentation techniques in Python.
 
---
 
## ❓ Business Questions
 
- Question 1: *What is the current churn situation?*
- Question 2: *What factors are associated with churn?*
- Question 3: *Which customer groups have high churn rates?*
- Question 4: *Which groups should the business focus on retaining?*
---
 
## 🗂 Dataset
 
| Attribute | Detail |
|---|---|
| **Source** | Kaggle |
| **Size** | 20,000 rows x 11 columns |
| **Time period** | Jun 2026 - Jul 2026 |
| **Format** | CSV |
 
**Dataset link:** [[link to dataset]](https://www.kaggle.com/datasets/sonalshinde123/customer-churn-prediction-dataset)
 
---
 
## 🛠 Tech Stack
 
<table>
<tr>
<td><b>Processing & Analysis</b></td>
<td>Python (Pandas, NumPy)</td>
</tr>
<tr>
<td><b>Visualization</b></td>
<td>Matplotlib, Seaborn</td>
</tr>
<tr>
<td><b>Statistics / ML</b></td>
<td>SciPy</td>
</tr>
<tr>
<td><b>Other Tools</b></td>
<td>Jupyter Notebook, Excel, Git</td>
</tr>
</table>
 
## 🔄 Analysis Workflow
 
```mermaid
flowchart LR
    A[Data Collection] --> B[Data Cleaning]
    B --> C[EDA - Exploratory Analysis]
    C --> D[In-depth Analysis / Modeling]
    D --> E[Visualization]
    E --> F[Conclusions & Recommendations]
```
 
1. **Data Collection & Cleaning**: handling missing values, outliers, format standardization.
2. **EDA (Exploratory Data Analysis)**: exploring distributions and correlations between variables.
3. **In-depth Analysis**: hypothesis testing, customer segmentation, predictive modeling (if applicable).
4. **Visualization**: building dashboards/charts to clearly present insights.
5. **Conclusion**: summarizing findings and providing concrete action recommendations.
---
 
## 💡 Key Insights
 
| Insight | Evidence |
|---|---|
| 🔹 Customers in their first 12 months churn at 47.58%, notably higher than the 31-32% churn rate seen among longer-tenured customers, after which the rate stabilizes | ![chart](./imgs/tenure_churn_rates.png) |
| 🔹 Customers with monthly contracts (month-to-month) have a significantly higher churn rate than those with annual contracts (a difference of 22.26 percentage points) | ![chart](./imgs/contract_churn_rates.png) |
| 🔹 Customers without tech support — regardless of whether they have online security — churn at more than double the rate of those with tech support. Online security alone has little protective effect | ![chart](./imgs/ts_os_churn_rates.png) |
 
---
 
## 📬 Contact
 
<div align="center">
**[Your Name]**
 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](#)
[![Gmail](https://img.shields.io/badge/Email-Contact-red?logo=gmail)](#)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-black?logo=googlechrome)](#)
 
</div>
