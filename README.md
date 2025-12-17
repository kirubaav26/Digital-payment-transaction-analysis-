# 📊 Digital Payment Transaction Analysis

This project presents an exploratory analysis of **150 digital payment transactions** using Microsoft Excel. The objective is to identify transaction-level patterns across transaction type, merchant category, sender age group, and geographic distribution within India.

---

## 📁 Dataset Overview
- Total records: **150 transactions**
- Key attributes include:
  - Transaction type (P2P, P2M, Bill Payment, Recharge)
  - Merchant category
  - Transaction amount
  - Sender age group
  - Sender bank
  - Timestamp (hour, weekday/weekend)
  - Sender state

The dataset is structured to simulate real-world digital payment behavior.

---

## 🛠 Tools & Techniques Used
- Microsoft Excel  
- Pivot Tables & Pivot Charts  
- Slicers for interactive filtering  
- Time-based analysis (hourly, weekday vs weekend)  
- Geographic visualization using map charts  

---

## 🔍 Key Analytical Insights

### Transaction Type Analysis
P2P and P2M transactions contribute the highest share of total transaction value, indicating strong adoption of digital payments for both peer transfers and merchant interactions. Recharge transactions contribute minimally due to their low-value nature.

### Merchant Category Patterns
Spending is concentrated in **Shopping and Utilities**, followed by Grocery and Fuel, suggesting that digital payments are widely used for essential and recurring expenses.

### Sender Age Group Behavior
Younger age groups (18–25 and 26–35) dominate transaction activity and value across most categories, reflecting higher digital payment adoption among younger and working-age users.

### Temporal Trends
Transaction activity peaks during mid-day to evening hours. Weekday transaction value exceeds weekend activity, indicating routine and work-related usage.

### Geographic Distribution
State-wise analysis highlights higher transaction value in economically active states such as Maharashtra, Karnataka, Gujarat, Uttar Pradesh, and West Bengal.  
Low-value transaction segments may appear less prominent in value-based maps due to scale differences.

---

## 🧠 Design Considerations
The dashboard emphasizes **transaction value–based analysis**. Certain low-value segments (e.g., recharge transactions or smaller demographic groups) may have limited geographic visibility, highlighting the importance of selecting appropriate metrics for visualization.

---

## 📌 Project Outcomes
This project demonstrates how pivot-based analytics and interactive Excel dashboards can be used to derive behavioral, temporal, and geographic insights from transaction-level data.
