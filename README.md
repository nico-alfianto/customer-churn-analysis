# 📊 Customer Churn Analysis – Telco Dataset

> **Predicting & Preventing Customer Churn with Data-Driven Insights**  
> A comprehensive EDA project to uncover why customers leave and how to keep them.

[![Python](https://img.shields.io/badge/Python-3.10-blue.svg)](https://www.python.org/)
[![Google Colab](https://img.shields.io/badge/Run%20on-Google%20Colab-F9AB00?logo=googlecolab)](https://colab.research.google.com/drive/11i-_gJWvSGnqqGsAzDdNsH9OomWPYVve)
[![Dataset](https://img.shields.io/badge/Dataset-Kaggle-20BEFF?logo=kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## 🎯 Project Overview

Customer churn costs telecom companies millions annually. This project dives deep into the **Telco Customer Churn dataset** to answer one critical business question: **Why do customers leave?**

The goal is to identify key churn drivers through exploratory data analysis and translate findings into actionable business strategies to boost customer retention.

## 📂 Dataset

This analysis uses the popular **Telco Customer Churn** dataset from Kaggle, widely adopted for customer retention studies.

**Source**: [Kaggle – Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

**Quick Stats:**
- **7,043** customer records
- **21 features** including demographics, services, account info, and churn status
- **Key variables**: `tenure`, `Contract`, `MonthlyCharges`, `PaymentMethod`, `Churn`

Perfect for practicing EDA, feature analysis, and business insight generation.

## 🛠️ Tech Stack

| Tool | Purpose |
| --- | --- |
| **Python** | Core programming language |
| **Google Colab** | Cloud-based notebook environment |
| **Pandas** | Data manipulation & cleaning |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical data visualization |

## 🔬 Methodology

This project follows the industry-standard **CRISP-DM** framework:

1. **Business Understanding** → Define churn problem & objectives
2. **Data Understanding** → Explore structure, types, and distributions  
3. **Data Preparation** → Handle missing values, encoding, feature engineering
4. **Exploratory Data Analysis** → Uncover patterns & correlations
5. **Insight Generation** → Translate patterns into business insights
6. **Business Recommendation** → Propose data-backed retention strategies

## 🔍 Key Findings

The EDA revealed 3 major churn drivers:

1. **Contract Type Matters** → Customers with `Month-to-Month` contracts show the **highest churn rate** compared to 1-year or 2-year contracts.
2. **New Customers Are at Risk** → Shorter `tenure` is strongly correlated with higher likelihood to churn.
3. **Price Sensitivity** → Higher `MonthlyCharges` are associated with increased churn risk, especially for fiber optic users.

## 💡 Business Recommendations

Based on the insights above, here are 3 actionable strategies:

1. **Incentivize Long-Term Contracts** → Offer discounts or perks for customers who switch from month-to-month to 1-year/2-year plans.
2. **Strengthen Onboarding & Early Engagement** → Create targeted retention programs for customers in their first 6 months.
3. **Review Pricing for High-Value Services** → Audit premium service pricing and bundle options to reduce price-driven churn.

## 📈 Results Summary

- Month-to-Month customers churn significantly more than long-term contract holders.
- Customers with tenure < 12 months are the most vulnerable segment.
- Increased monthly charges directly correlate with higher churn probability.

## 🚀 Run the Analysis

Want to see the full analysis with code and visualizations?

**▶️ Open in Google Colab**: [Customer Churn Analysis Notebook](https://colab.research.google.com/drive/11i-_gJWvSGnqqGsAzDdNsH9OomWPYVve)

---

**Let's Connect**  
If you have feedback or want to discuss this project, feel free to reach out!
