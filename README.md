# 🏦 Credit Risk Modeling & Portfolio Analytics 
### *End-to-End Probability of Default (PD) Engine*

##  Project Overview
This project focuses on quantifying credit risk for retail lending by developing a probabilistic model to predict borrower default. By integrating **Economic Theory** with **Data Science**, I built a functional pipeline that moves from raw data cleaning in Excel to predictive modeling in Python, culminating in an executive-level Power BI dashboard.



---

##  Technical Stack
* **Analysis & ETL:** Python (Pandas, NumPy), Excel (Power Query)
*  **Modeling:** Scikit-Learn (Logistic Regression)
* **Visualization:** Power BI (DAX, Star Schema Modeling) 
* **Environment:** Google Colab / Jupyter Notebook 

---

##  Key Methodology & Results
![Credit Risk Dashboard](https://github.com/dhrithi21/Credit-Risk-Analysis/blob/main/portfolio KPIs.png.png?raw=true)
![Credit Risk Dashboard](https://github.com/dhrithi21/Credit-Risk-Analysis/blob/main/RISK SEGMENTATION.png.png?raw=true)
![Credit Risk Dashboard](https://github.com/dhrithi21/Credit-Risk-Analysis/blob/main/overall table analysis.png.png?raw=true)
### 1. Feature Engineering
* Calculated critical solvency ratios: **Debt-to-Income (DTI)** and **Loan-to-Income (LTI)**.
* Standardized financial variables to ensure unbiased model coefficients.

### 2. Predictive Modeling (Logistic Regression)
* Implemented a **Logistic Regression** classifier to estimate P(Default=1|X).
* Achieved an **AUC-ROC score of 0.72**, demonstrating strong discriminatory power in distinguishing between high and low-risk borrowers.



### 3. Risk Segmentation & Calibration
* Segmented the portfolio into **Low, Medium, and High-Risk** tiers.
* Validated model **Monotonicity**: confirmed that realized default rates increase consistently with predicted risk buckets.

---

##  Strategic Business Insights
* **Risk-Based Pricing:** Identified segments where interest rate premiums are required to offset **Expected Loss (EL)**.
* **Policy Recommendations:** Proposed a **40% DTI hard-cap** for new applicants to reduce portfolio exposure to high-probability default clusters.
* **Portfolio Concentration:** Utilized Power BI to identify geographical and demographic "Risk Clusters" for real-time monitoring.

---

## Repository Structure
* `CREDIT_RISK_MODEL.ipynb`: Full Python modeling workflow.
*   `Report.pdf`: Comprehensive technical whitepaper and executive summary.
* [cite_start]`Data/`: Cleaned dataset used for the analysis.

---
**Author:** DHRITHI MANGAL  
**Field:** B.A. Economics (1st Year)  

