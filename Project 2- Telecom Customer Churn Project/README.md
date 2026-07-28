# Customer Churn Analysis Dashboard

An interactive **Power BI Dashboard** designed to analyze customer churn patterns, identify key retention risks, and provide actionable insights for business decision-making.

---

## 📌 Executive Summary

Customer churn is a critical metric for subscription-based businesses. This project provides a comprehensive end-to-end analysis of customer demographic, contractual, and service usage data to understand why customers leave and identify high-risk customer segments.

### Key Performance Indicators (KPIs)
* **Total Customers:** 7,032
* **Churn Rate:** 26.58%
* **Churned Customers:** 1,869

---

## 💡 Key Insights & Findings

1. **Contract Type Impact:** Customers on **Month-to-Month contracts** exhibit a significantly higher churn rate compared to those on One-Year or Two-Year contracts. Long-term commitment contracts heavily improve retention.
2. **Tenure Dynamics:** New customers in their early tenure (**0–12 months**) are at the highest risk of churn. Churn rate steadily decreases as customer tenure increases (**49–72 months**).
3. **Internet Service Comparison:** **Fiber Optic** service subscribers experience noticeably higher churn rates compared to **DSL** users, pointing toward potential pricing or service quality friction points.
4. **Payment Method Influence:** Customers using **Electronic Check** show substantially higher churn rates compared to automated payment methods like Credit Card or Bank Transfer.

---

## 🛠️ Tools & Technologies Used

* **Power BI Desktop:** Dashboard visualization, layout design, and interactivity.
* **Power Query:** Data extraction, cleaning, transformation, and profiling.
* **DAX (Data Analysis Expressions):** Custom measures and calculated columns for key performance indicators and churn rate percentage calculations.
* **Data Modeling:** Star schema modeling, relationship mapping, and parameter filtering.

---

## 📊 Dashboard Overview

The interactive dashboard includes:
* **KPI Header Cards:** Immediate overview of total customer volume, churn count, and overall churn rate.
* **Churn by Tenure Group:** Stacked bar chart analyzing churn across tenure brackets.
* **Customer Distribution:** Donut chart illustrating total vs. churned customer breakdown.
* **Churn by Contract Type & Service:** Visual breakdowns evaluating contract terms and internet connection types.
* **Churn by Payment Method:** Horizontal bar analysis across payment types.
* **Interactive Slicers/Filters:** Filter seamlessly by Contract Type and Gender.

---