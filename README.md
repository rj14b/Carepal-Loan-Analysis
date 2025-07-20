
# 🩺 Carepal Power BI Dashboard — Healthcare Loan Intelligence Made Visual

A powerful Power BI dashboard that visualizes critical insights across healthcare-related loans analyzing loan disbursement, default risks, user demographics, repayment trends, and medical category performance. Designed to help healthcare lenders and analysts make smarter, data-informed financial decisions.

---

## 📌 Project Purpose

This dashboard transforms raw healthcare lending data into actionable insights. By unifying patient demographics, loan behavior, and medical category trends, Carepal enables:

- **Risk-aware lending decisions**
- **Enhanced loan portfolio management**
- **Transparent performance tracking**

Tailored for credit teams, underwriting professionals, and healthcare finance analysts.

---

## 🧰 Tech Stack

| Tool / Language        | Role                                          |
|------------------------|-----------------------------------------------|
| **Power BI Desktop**   | Dashboard development & visualization         |
| **DAX**                | Dynamic measures & calculated KPIs            |
| **Power Query**        | Data cleaning, shaping, and transformation    |
| **PBIX / PDF Files**   | `.pbix` for development, `.pdf` for preview   |

---

## 🔄 ETL Pipeline: Data Cleaning & Modeling

### 🧹 Cleaning
- Removed duplicates and null entries across key tables  
- Standardized date formats, medical category names, and user info  
- Ensured consistent formats for amounts and durations  

### 🔄 Transformation
- Created derived fields: `Age Group`, `Loan Duration`, `Membership Status`  
- Categorized risk levels (Low, Medium, High, Critical)  
- Extracted month/year for trend visuals  
- Mapped categories to risk exposure and efficiency metrics

### 🧠 Data Modeling
- Established relationships across **Users**, **Loans**, **Medical Categories**, and **Repayments**  
- Built key DAX measures like:
  - `Loan Default Rate`
  - `Repayment Rate`
  - `Avg Loan Amount per User`
  - `Avg Interest Rate`
  - `Medical Risk Exposure`

---

## 🗂 Data Source Summary

Synthetic data simulating healthcare lending scenarios, including:
- Loan application & disbursement records  
- Patient/user demographics  
- Medical service categories (e.g., Dental, Surgery, Pharmacy)  
- Risk classification per loan  
- Premium membership and repayment status  

---

## 🌟 Key Business Goals

### 💼 The Problem

Healthcare loans span multiple services and user types, but data is often fragmented. Without consolidation, it’s hard to spot high-risk zones, creditworthy borrowers, or trends in disbursement and repayment.

### 🎯 Dashboard Objectives

- Centralize medical loan data for smarter financial decisions  
- Monitor risk, repayments, and defaults by category  
- Segment performance by age group, gender, and membership status  
- Support loan policy optimization through clear visuals  

---

## 📊 Dashboard Pages & Key Visuals

### 🟡 **1.Loan Overview**
| 📌 Metric / Chart                  | 🔍 Insight                                                                 |
|----------------------------------|---------------------------------------------------------------------------|
| KPIs                             | Total Loans, Amount Disbursed, Defaulted, Repaid, Pending, Interest Rate |
| Line Chart                       | Monthly Loan Disbursement Trends                                          |
| Stacked Bar (Gender × Age)       | Loan Amounts by Demographic Group                                        |
| Bar Chart                        | Loan Distribution across Medical Categories                              |

![Loan Overview](images/Loan%20Overview.png)


---

### 🟢 **2. Medical Category Performance**
| 📌 Metric / Chart                  | 🔍 Insight                                                                 |
|----------------------------------|---------------------------------------------------------------------------|
| KPIs                             | Default Rate, Repayment Rate, Avg Loan Duration, Premium Members         |
| Risk Bar Chart                   | Risk Segmentation by Medical Category (Critical to Low)                 |
| Efficiency Matrix                | Avg Processing Time vs Approval Rate                                     |
| Risk Exposure Table              | Breakdown of loan exposure by risk level                                 |
| Avg Loan Amount Chart            | Financial comparison across medical services                             |


![Medical Category Performance](images/Medical%20Category.png)


---

## 👥 Who Is This For?

- **🏥 Healthcare Lenders** – Understand loan risk patterns  
- **📊 Credit Analysts** – Discover repayment bottlenecks  
- **💡 Policy Makers** – Refine lending policies  
- **🔎 Executives** – Gain high-level portfolio insights  

---

## 📸 Screenshots (Upload in `images/` folder)

| Page                     | Preview                               |
|--------------------------|----------------------------------------|
| Home     | ![Home](images/Home.png)|
| Loan Overview       | ![Loan Overview](images/Loan%20Overview.png)|
| Medical Category Performance |![Medical Category Performance](images/Medical%20Category.png)          |

---


---

> 🧾 **File Name**: `README.md`  
> 🗓️ **Author**: [Your Name or GitHub Handle]
