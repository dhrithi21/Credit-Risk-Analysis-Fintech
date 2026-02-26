# 🏦 Credit Risk Modeling & Portfolio Analytics 
### *End-to-End Probability of Default (PD) Engine*

##  Project Overview
This project focuses on quantifying credit risk for retail lending by developing a probabilistic model to predict borrower default. By integrating **Economic Theory** with **Data Science**, I built a functional pipeline that moves from raw data cleaning in Excel to predictive modeling in Python, culminating in an executive-level Power BI dashboard.



---

##  Technical Stack
* [cite_start]**Analysis & ETL:** Python (Pandas, NumPy), Excel (Power Query) [cite: 1]
* [cite_start]**Modeling:** Scikit-Learn (Logistic Regression) [cite: 1]
* [cite_start]**Visualization:** Power BI (DAX, Star Schema Modeling) [cite: 1]
* [cite_start]**Environment:** Google Colab / Jupyter Notebook [cite: 1]

---

##  Key Methodology & Results
### 1. Feature Engineering
* [cite_start]Calculated critical solvency ratios: **Debt-to-Income (DTI)** and **Loan-to-Income (LTI)**[cite: 1].
* [cite_start]Standardized financial variables to ensure unbiased model coefficients[cite: 1].

### 2. Predictive Modeling (Logistic Regression)
* [cite_start]Implemented a **Logistic Regression** classifier to estimate $P(Default=1|X)$[cite: 1].
* [cite_start]Achieved an **AUC-ROC score of 0.72**, demonstrating strong discriminatory power in distinguishing between high and low-risk borrowers[cite: 1].



### 3. Risk Segmentation & Calibration
* [cite_start]Segmented the portfolio into **Low, Medium, and High-Risk** tiers[cite: 1].
* [cite_start]Validated model **Monotonicity**: confirmed that realized default rates increase consistently with predicted risk buckets[cite: 1].

---

##  Strategic Business Insights
* [cite_start]**Risk-Based Pricing:** Identified segments where interest rate premiums are required to offset **Expected Loss (EL)**[cite: 1].
* [cite_start]**Policy Recommendations:** Proposed a **40% DTI hard-cap** for new applicants to reduce portfolio exposure to high-probability default clusters[cite: 1].
* [cite_start]**Portfolio Concentration:** Utilized Power BI to identify geographical and demographic "Risk Clusters" for real-time monitoring[cite: 1].

---

## Repository Structure
* [cite_start]`CREDIT_RISK_MODEL.ipynb`: Full Python modeling workflow[cite: 1].
* [cite_start]`Report.pdf`: Comprehensive technical whitepaper and executive summary[cite: 1].
* [cite_start]`Data/`: Cleaned dataset used for the analysis[cite: 1].

---
**Author:** [DHRITHI MANGAL]  
**Field:** B.A. Economics (1st Year)  

