# 📊 Zalando FY24: EBIT Sensitivity & Margin Resilience Model

## 🎯 Project Objective
This project was developed to simulate how **Zalando SE's** operating profit (EBIT) reacts to market volatility. Using data from the **FY 2024 Annual Report**, I built a stress-test model to evaluate margin safety under different revenue scenarios.

## 🛠️ Technical Features
* **Driver-Based Modeling:** Separated costs into **Variable** (COGS, Marketing) and **Fixed** (Admin, Other Operating) to demonstrate the impact of **Operating Leverage**.
* **Scenario Manager:** Dynamic logic allowing users to toggle between **Base Case**, **Worst Case (-10%)**, and **Best Case (+10%)**.
* **Financial Visualization:** Included a Waterfall (Bridge) chart to visually reconcile the delta between revenue loss and EBIT contraction.
* **Data Integrity:** Implemented "Zero-Check" formulas to ensure the balance sheet and income statement logic remains error-free.

## 📈 Key Controlling Insights
* **The "Fixed Cost Trap":** My model reveals that a 10% decline in revenue results in a significant EBIT margin drop because **Admin and Logistics overheads** do not scale down linearly with sales.
* **Sensitivity:** Fulfillment remains the highest cost driver (~23% of revenue), making it the primary lever for margin protection during downturns.

## 📁 Files in this Repository
* `Zalando_Analysis_2024.xlsx`: The full interactive model.
* `Dashboard_Preview.pdf`: A high-level summary for quick management review.

---
**Contact:** [Shweta Bhingare] | [www.linkedin.com/in/shweta-bhingare]
