# 🔍 Fraud and Risk Analysis Dashboard — Power BI

A multi-dimensional fraud detection and risk analysis project built in Power BI,
combining three domain-specific datasets — Credit Card transactions, E-Commerce
activity, and User financial flows — into a unified analytical report.
This dashboard is designed to help analysts and decision-makers identify
fraudulent patterns, assess risk levels, and monitor suspicious behavior
across different transaction ecosystems.

---

## 📊 Dashboard Overview

### 1. Credit Card Fraud and Risk Analysis
Analyzes **10,000 credit card transactions** to surface fraud signals across time,
merchant categories, and transaction amounts.

**Key Metrics:**
- 🔢 Total Transactions: **10K**
- 🚨 Fraud Transactions: **151**
- 💰 Avg Fraud Amount: **₹216**
- 📉 Fraud Rate: **2%**

**Visuals:**
- Timeline of Fraud by Transaction Hour
- Merchant Category by Fraud (Food, Clothing, Travel, Grocery, Electronics)
- Transaction Amount Distribution by Fraud
- Foreign vs Domestic Transaction Breakdown
- High Risk / Low Risk Filter Slicer

---

### 2. E-Commerce Fraud and Risk Analysis
Examines **623 e-commerce transactions** to distinguish normal vs suspicious
customer behavior across payment methods and order volumes.

**Key Metrics:**
- 🛒 Total Transactions: **623**
- 💳 Total Payments: **342**
- 📦 Total Orders: **478**
- ⚠️ Suspicious Customers: **18.45%** | Normal: **81.55%**

**Visuals:**
- Suspicious vs Normal Customer Donut Chart
- Transaction Status by Order Payment (Normal / Suspicious / Total)
- Customer Count by Payment Method
- Customer Count by Number of Orders

---

### 3. Users Fraud and Risk Analysis
Tracks large-scale **financial user transactions** totaling over **5.32 billion**
in balance flow, analyzing balance drain patterns and fraud probability
across transaction types.

**Key Metrics:**
- 🏦 Total New Balance: **5.32bn**
- 🏦 Total Old Balance: **5.21bn**
- 🚩 Total Fraud Cases: **40**
- 🔎 Flagged Fraud: **0** (accuracy matrix: 4959 true negatives)

**Visuals:**
- Balance Drain Pattern Line Chart (5-step flow)
- Fraud Probability by Transaction Type (Payment, Cash-In, Cash-Out, Transfer, Debit)
- Balance Drain Scatter Plots (Old vs New Balance)
- Fraud Detection Accuracy Matrix

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Power BI | Dashboard design & data visualization |
| Microsoft Excel | Data preprocessing & cleaning |
| DAX | Custom measures & calculated columns |
| Power Query | Data transformation & merging |

---

## 💡 Key Insights

- **Credit card fraud** peaks during specific transaction hours, with Food and
  Clothing as the highest-risk merchant categories.
- **E-commerce suspicious activity** accounts for nearly **1 in 5 customers**,
  with irregular payment patterns as a key signal.
- **User-level fraud** is concentrated in **PAYMENT and CASH_OUT** transaction
  types, with large balance drains as a reliable fraud indicator.
- Combining all three datasets reveals cross-domain fraud patterns that
  individual dashboards cannot capture alone.

---

## 🚀 How to Use

1. Clone or download this repository
2. Open `.pbix` files in **Power BI Desktop**
3. Connect to the datasets in the `/datasets` folder if prompted
4. Use the slicers (High Risk / Low Risk, Normal / Suspicious) to filter views
5. Navigate between report pages to explore each fraud domain

---

## 👩‍💻 Author

**Sanika**
BCA Student | Data Analyst | Creative Designer

---

## 📌 Note

This project was built for analytical and academic purposes using
synthetic/publicly available datasets. All insights are exploratory
and not intended for production fraud detection systems.




