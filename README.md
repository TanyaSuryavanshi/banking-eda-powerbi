

# Banking Data Analysis & Power BI Dashboard

## Project Overview

This project analyzes banking customer data to understand customer demographics, income levels, loans, deposits, account balances, customer loyalty, and risk-related patterns.

The project combines **Python-based Exploratory Data Analysis (EDA)** with a **Power BI dashboard** to transform raw banking data into meaningful business insights and KPIs.


---

## Objectives

* Analyze banking customer demographics and financial behavior
* Understand customer income distribution
* Analyze loan and deposit patterns
* Compare financial behavior across income bands
* Identify patterns across nationality, loyalty, and risk categories
* Analyze different account types and their balances
* Calculate meaningful financial KPIs
* Build interactive Power BI dashboards
* Generate business-oriented insights and recommendations

---

## Tech Stack

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**
* **Power BI**
* **DAX**

---

## Project Structure

```text
banking-data-analysis-powerbi/
│
├── Banking.csv
│
├── BankEDA.ipynb 
│
├── Banking_Dashboard.pbix
│
├── images/
│   ├── Home.png
│   ├── Loan analysis.png
│   └── Deposit Analysis.png
│   └── Summary.png
│
├── README.md
```

---

## Exploratory Data Analysis

The Python notebook covers the complete EDA workflow:

### Data Understanding

* Dataset shape and structure
* Column inspection
* Descriptive statistics
* Data types
* Basic dataset exploration

### Data Quality

* Missing-value checks
* Duplicate-record checks
* Data-type validation
* Basic data preparation

### Customer Analysis

* Nationality distribution
* Loyalty classification
* Risk weighting
* Credit card ownership
* Properties owned
* Customer income bands

### Income Analysis

Customers are categorized into income bands to compare their financial behavior:

* Low Income
* Mid Income
* High Income

The analysis compares income groups based on loans, deposits, risk, and other banking characteristics.

### Loan Analysis

The project analyzes:

* Bank Loans
* Business Lending
* Credit Card Balance
* Total Loan Exposure
* Loans by nationality
* Loans by occupation
* Loan exposure by income band

### Deposit & Account Analysis

The project examines:

* Bank Deposits
* Checking Accounts
* Savings Accounts
* Foreign Currency Accounts
* Credit Card balances
* Deposit behavior across customer segments

---

## Derived Business Metrics

Additional metrics were created to make the analysis more business-focused.

### Total Loan Exposure

```text
Total Loan Exposure =
Bank Loans + Business Lending + Credit Card Balance
```

### Loan-to-Deposit Ratio

```text
Loan-to-Deposit Ratio =
Total Loan Exposure / Bank Deposits
```

The Loan-to-Deposit Ratio is used to compare lending exposure with the bank's deposit base.

---

## Power BI Dashboard

The Power BI dashboard presents banking KPIs and financial trends in an interactive format.

### Key KPIs

* Total Clients
* Total Loan
* Bank Loan
* Business Lending
* Total Deposit
* Total Fees
* Bank Deposit
* Checking Account Amount
* Savings Account Amount
* Foreign Currency Account Amount
* Credit Card Balance
* Engagement Length

### Dashboard Pages

#### Home

Provides an overall view of important banking KPIs and customer metrics.

#### Loan Analysis

Focuses on loan-related metrics including bank loans, business lending, credit card balances, and loan exposure.

#### Deposit Analysis

Analyzes deposits and different customer account balances.

#### Summary Dashboard

Provides a consolidated view of key banking metrics and customer financial behavior.

---

## DAX

The Power BI analysis uses DAX functions and calculated measures such as:

* `SUM`
* `DISTINCTCOUNT`
* `SUMX`
* `SWITCH`
* `DATEDIFF`

These calculations are used to create KPIs, classifications, and dashboard metrics.

---

## Key Business Insights

The notebook automatically generates data-backed insights covering areas such as:

* Largest customer income segment
* Nationality with the highest total bank loans
* Account type with the highest total balance
* Largest component of loan exposure
* Loyalty segment with the highest average deposit
* Risk category with the highest average bank loan
* Relationship between income and bank loans
* Relationship between income and bank deposits

The exact values are calculated directly from the dataset when the notebook is executed.

---

## Business Recommendations

Based on the analysis, banking teams can use customer segmentation and financial behavior to:

* Identify customer groups with higher lending potential
* Monitor high loan-exposure segments
* Compare deposits against lending exposure
* Understand customer account preferences
* Develop targeted financial products for different income segments
* Monitor risk-related customer groups
* Improve customer engagement using loyalty-based segmentation

---


## Dashboard Preview

### Home Dashboard
<img width="620" height="344" alt="Home" src="https://github.com/user-attachments/assets/4ac06bd7-68b8-4c2a-9b21-4dc3c2df506f" />


### Loan Analysis
<img width="623" height="347" alt="Loan analysis" src="https://github.com/user-attachments/assets/b29cb7b9-2513-49ce-a51e-32400f4efd65" />



### Deposit Analysis
<img width="626" height="347" alt="Deposit Analysis" src="https://github.com/user-attachments/assets/d41fa64b-9bc9-4212-91df-5788d15382d7" />




### Summary Dashboard
<img width="620" height="349" alt="Summary" src="https://github.com/user-attachments/assets/c123a635-df4e-4dae-80f6-725e4716c9c7" />



---

## Project Author

**Tanya Suryavanshi**

GitHub:
https://github.com/TanyaSuryavanshi
