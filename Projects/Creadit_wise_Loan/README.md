# CreditWise Loan Approval Prediction System

## 📌 Project Overview

CreditWise Loan System is a Machine Learning project designed to help **SecureTrust Bank** automate its loan approval process.

Currently, the bank uses a manual verification process where loan officers evaluate applications based on income, employment details, credit history, documents, and other information.

This manual process is:

- Time-consuming
- Biased
- Inconsistent

As a result:

1. Good customers may get rejected, causing loss of business.
2. High-risk customers may get approved, causing financial losses.

The goal of this project is to build an **intelligent Machine Learning-based loan approval system** that analyzes applicant information and predicts whether a loan should be **Approved or Rejected** before final human verification.

---

## 🎯 Objective

The main objective of this project is to develop a Machine Learning classification model that can:

- Analyze historical loan application data
- Identify patterns in customer records
- Predict loan approval decisions
- Provide fast and consistent predictions
- Support human loan officers in the decision-making process

### Target Variable

`Loan_Approved`

- `1` → Approved
- `0` → Rejected

---

## 📊 Dataset Description

Each row in the dataset represents one loan applicant.

The dataset contains personal, financial, employment, and credit-related information.

### Dataset Features

| Column | Description |
|---|---|
| `Applicant_ID` | Unique applicant ID |
| `Applicant_Income` | Monthly income of applicant |
| `Coapplicant_Income` | Monthly income of co-applicant |
| `Employment_Status` | Salaried / Self-Employed / Business |
| `Age` | Applicant age |
| `Marital_Status` | Married / Single |
| `Dependents` | Number of dependents |
| `Credit_Score` | Credit bureau score |
| `Existing_Loans` | Number of already running loans |
| `DTI_Ratio` | Debt-to-Income ratio |
| `Savings` | Savings balance |
| `Collateral_Value` | Value of collateral provided |
| `Loan_Amount` | Loan amount requested |
| `Loan_Term` | Loan duration in months |
| `Loan_Purpose` | Home / Education / Personal / Business |
| `Property_Area` | Urban / Semi-Urban / Rural |
| `Education_Level` | Graduate / Postgraduate / Undergraduate |
| `Gender` | Male / Female |
| `Employer_Category` | Govt / Private / Self |
| `Loan_Approved` | Target variable: 1 = Approved, 0 = Rejected |

---

## 🧠 Machine Learning Problem

This is a **Supervised Machine Learning Classification Problem**.

### Input

Applicant's:

- Income
- Employment status
- Age
- Credit score
- Existing loans
- DTI ratio
- Savings
- Collateral value
- Loan amount
- Loan term
- Loan purpose
- Property area
- Education level
- Gender
- Employer category
- And other relevant information

### Output

```text
Loan Approved
      ↓
  1 → Approved
  0 → Rejected