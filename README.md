# 📊 Telecom Customer Churn Analysis

## 📌 Project Overview

Customer churn is one of the most critical challenges faced by telecom companies. This project focuses on analyzing customer behavior, identifying churn drivers, and generating actionable business insights to improve customer retention.

Using Exploratory Data Analysis (EDA), statistical visualization, and customer segmentation techniques, this project investigates how demographics, contract types, billing methods, service subscriptions, tenure, and monthly charges influence customer churn.

The dataset contains **7,043 telecom customers**, with **1,869 churned customers** and **5,174 active customers**.

### Overall Churn Rate

* Active Customers: **73.46%**
* Churned Customers: **26.54%**

This indicates that approximately **1 out of every 4 customers leaves the company**, making churn reduction a significant business priority.

---

# 🎯 Business Objectives

* Identify the key factors contributing to customer churn.
* Analyze customer demographics and service usage patterns.
* Discover high-risk customer segments.
* Generate actionable recommendations to improve retention.
* Support future development of churn prediction models.

---

# 🛠️ Technologies & Libraries Used

### Programming Language

* Python

### Libraries

* **NumPy** – Numerical computations
* **Pandas** – Data cleaning and manipulation
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization

### Environment

* Jupyter Notebook

---

# 📂 Dataset Features

The dataset includes:

* Customer Demographics
* Gender
* Senior Citizen Status
* Partner & Dependents Information
* Contract Type
* Payment Method
* Tenure
* Monthly Charges
* Total Charges
* Internet Services
* Online Security
* Device Protection
* Tech Support
* Churn Status

---

# 📊 Exploratory Data Analysis Performed

## Customer Distribution Analysis

* Churn vs Retained Customers
* Churn Rate Calculation

## Demographic Analysis

* Gender vs Churn
* Senior Citizen vs Churn
* Partner vs Churn
* Dependents vs Churn

## Service Analysis

* Internet Service Type
* Online Security
* Online Backup
* Device Protection
* Tech Support

## Billing Analysis

* Contract Type
* Payment Methods
* Paperless Billing

## Financial Analysis

* Monthly Charges Distribution
* Total Charges Analysis

## Advanced Visualization

* Countplots
* Histograms
* Boxplots
* Correlation Analysis
* 3D Scatter Plot
* Customer Segmentation Analysis

---

# 🔍 Key Insights

## 1️⃣ Senior Citizens Have Higher Churn Risk

* Senior Citizen Churn Rate: **41.7%**
* Non-Senior Churn Rate: **23.6%**

Senior customers are significantly more likely to leave the service.

---

## 2️⃣ Low Tenure Customers Churn More

Customers within their first year show the highest churn rates.

### Insight:

The first 12 months are the most critical period for customer retention.

---

## 3️⃣ Contract Type is the Strongest Churn Driver

| Contract Type  | Churn Rate |
| -------------- | ---------- |
| Month-to-Month | 42.7%      |
| One-Year       | 11.3%      |
| Two-Year       | 2.8%       |

### Insight:

Customers on month-to-month contracts are approximately **15x more likely to churn** than customers on two-year contracts.

---

## 4️⃣ Paperless Billing Customers Churn More

| Billing Type        | Churn Rate |
| ------------------- | ---------- |
| Paperless Billing   | 33.6%      |
| Traditional Billing | 16.3%      |

Paperless billing users show significantly higher churn behavior.

---

## 5️⃣ Payment Method Impacts Retention

Highest churn was observed among customers using:

* Electronic Check → 45.3%
* Mailed Check → 19.1%
* Bank Transfer (Auto) → 16.7%
* Credit Card (Auto) → 15.2%

### Insight:

Electronic check users are the most vulnerable customer segment.

---

## 6️⃣ High Monthly Charges Increase Churn

Customers paying higher monthly fees are more likely to discontinue services.

### Insight:

Pricing sensitivity plays a major role in customer retention.

---

## 7️⃣ Additional Services Reduce Churn

Customers lacking the following services show higher churn:

* Online Security
* Online Backup
* Device Protection
* Tech Support

### Insight:

Value-added services increase customer loyalty.

---

## 8️⃣ Internet Service Type Matters

Fiber Optic customers demonstrate higher churn compared to DSL users.

Possible reasons:

* Higher pricing
* Greater customer expectations
* Service quality concerns

---

## 9️⃣ Family Status Influences Retention

Customers with:

* Partners
* Dependents

are more likely to remain with the company.

---

## 🔟 Gender Has Minimal Impact

Male and female customers exhibit nearly identical churn behavior.

### Insight:

Gender is not a significant churn predictor.

---

# 🎯 High-Risk Customer Profile

A customer is most likely to churn if they have:

✅ Month-to-Month Contract

✅ Electronic Check Payment Method

✅ High Monthly Charges

✅ Low Tenure

✅ No Online Security

✅ No Tech Support

✅ Senior Citizen Status

---

# 📈 Business Recommendations

1. Convert month-to-month customers into annual plans.
2. Provide discounts for long-term contracts.
3. Promote automatic payment methods.
4. Strengthen onboarding during the first year.
5. Bundle security and support services.
6. Develop retention programs for senior citizens.
7. Review pricing strategies for high-paying customers.
8. Improve Fiber Optic customer experience.
9. Build a Machine Learning churn prediction model.

---

# 📊 Future Enhancements

* Churn Prediction using Machine Learning
* Customer Lifetime Value Analysis
* Retention Campaign Dashboard
* Power BI Interactive Dashboard
* Customer Segmentation using Clustering
* Predictive Analytics for Churn Prevention

---

# 📌 Conclusion

This analysis identified **Contract Type, Tenure, Payment Method, Monthly Charges, Senior Citizen Status, and Service Adoption** as the strongest predictors of customer churn.

With a churn rate of **26.54%**, telecom companies can significantly improve customer retention by focusing on high-risk customer groups and implementing targeted retention strategies. The insights generated from this project can help businesses reduce churn, increase customer lifetime value, and improve long-term profitability.

---

### ⭐ If you found this project useful, don't forget to star the repository!
