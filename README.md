# Tata Motors — Business Performance Diagnosis

## 📊 Project Overview

This project analyzes quarterly business performance using **Python, pandas, Power BI and DAX**.

The objective is to diagnose changes in revenue, expenses, operating profitability and net profitability, identify the major drivers of performance, and convert the analysis into actionable business recommendations.

> **Note:** This repository is an illustrative learning/portfolio case study. The dataset used for analysis has been created for educational purposes and should not be treated as verified Tata Motors financial reporting.

---

## 🎯 Business Problem

Management needs to understand:

- Is revenue growing or declining?
- How are expenses changing relative to revenue?
- Which quarters experienced profitability pressure?
- What is driving changes in operating margin?
- Are non-operating factors influencing net profit?
- What actions could improve future performance?

---

## 🛠️ Tools & Technologies

- **Python**
- **pandas**
- **NumPy**
- **Jupyter Notebook**
- **Microsoft Power BI**
- **DAX**
- **Microsoft Excel**

---

## 🔄 Project Workflow

```text
Data Collection
      ↓
Data Understanding
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Revenue & Expense Analysis
      ↓
Profitability Analysis
      ↓
Root Cause Diagnosis
      ↓
Power BI Dashboard
      ↓
Business Recommendations
```

---

## 📁 Project Structure

```text
tata-motors-business-performance-diagnosis/
│
├── data/
│   └── Tata_Motors_Business_Performance_Diagnosis_Dataset.xlsx
│
├── python/
│   └── business_performance_analysis.ipynb
│
├── powerbi/
│   └── Tata_Motors_Business_Performance_Diagnosis.pbix
│
├── dashboard/
│   ├── executive_overview.png
│   └── root_cause_deep_dive.png
│
├── documentation/
│   └── executive_report.pdf
│
└── README.md
```

---

## 🔍 Analysis Performed

### Revenue Analysis

Analyzed quarterly revenue trends and compared FY24 with FY25 to identify periods of growth and decline.

### Expense Analysis

Analyzed:

- Total expenses
- Expense growth
- Expense-to-sales ratio
- Quarterly cost efficiency

### Profitability Analysis

Calculated and analyzed:

- Operating Profit
- Operating Margin %
- Net Profit
- Net Margin %
- Revenue YoY Growth

### Root Cause Analysis

The analysis focuses on understanding whether changes in profitability are associated with:

- Revenue movement
- Cost intensity
- Operating margin changes
- Interest expenses
- Other income
- Depreciation

---

## 📈 Power BI Dashboard

### Executive Overview

![Executive Overview](executive_overview.png)

The first dashboard page provides an executive-level view of:

- Total Revenue
- Revenue YoY Growth
- Operating Profit
- Operating Margin
- Net Profit
- Quarterly Revenue Trend
- Operating Margin Trend
- FY24 vs FY25 Revenue Comparison

---

### Root Cause Deep Dive

![Root Cause Deep Dive](root_cause_deep_dive.png)

The second dashboard page focuses on diagnosing performance changes through:

- Revenue vs Expenses
- Expense-to-Sales %
- Operating Margin
- Other Income vs Interest Expense
- Quarterly profitability trends

---

## 📌 Key Findings

Based on the illustrative dataset:

- FY25 revenue was lower than FY24.
- Revenue pressure was particularly visible during FY25 Q2–Q3.
- Expense-to-sales increased during the weaker FY25 quarters.
- Operating margin declined during Q2–Q3 FY25.
- Q4 FY25 showed a recovery in operating margin and cost efficiency.
- Lower interest and depreciation provided some offset to operating pressure.
- Other income had a noticeable impact on selected quarters.

---

## 💡 Business Recommendations

### 1. Improve Cost Efficiency

Monitor cost components and identify areas where expenses can be reduced without affecting operational performance.

### 2. Investigate Revenue Decline

Perform further analysis by:

- Vehicle segment
- Product
- Geography
- Volume
- Pricing

to identify the specific sources of revenue pressure.

### 3. Focus on Sustainable Profitability

Track operating profit and operating margin separately from other income and financing-related factors to understand the underlying business performance.

---

## 📊 Key KPIs

| KPI | Purpose |
|---|---|
| Total Revenue | Measures overall sales performance |
| Revenue YoY Growth | Measures year-over-year revenue change |
| Total Expenses | Measures cost level |
| Expense-to-Sales % | Measures cost efficiency |
| Operating Profit | Measures core operating profitability |
| Operating Margin % | Measures operating efficiency |
| Net Profit | Measures bottom-line profitability |
| Net Margin % | Measures profitability after expenses |

---

## 👨‍💻 Skills Demonstrated

**Data Analysis:** Python, pandas, NumPy, EDA

**Business Intelligence:** Power BI, DAX, Data Modeling

**Business Analysis:** KPI Analysis, Trend Analysis, Root Cause Analysis

**Data Visualization:** Power BI Dashboard Design

---

## 🚀 Future Improvements

Future versions of the project could include:

- Segment-level analysis
- Geographic analysis
- Product-level performance
- Volume and pricing analysis
- Forecasting
- Advanced statistical analysis
- Automated data refresh
- Additional Power BI drill-through pages

---

## 📬 Feedback

Feedback and suggestions for improving the analysis are welcome.
