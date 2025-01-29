# Retail Store Sales Analytics Dashboard

## Overview
This Power BI dashboard provides an in-depth analysis of retail store sales. It highlights key performance indicators (KPIs) and interactive visualizations to help understand revenue trends, customer insights, and geographical sales distribution.

### **Dashboard Link**
https://github.com/Tmuley/Online-Retail-store

---

## Problem Statement
The retail store experiences seasonal sales fluctuations and varying demand across different regions. This dashboard aims to:
- Identify revenue trends and seasonality in sales.
- Highlight high-potential markets for expansion.
- Examine customer purchasing behavior and dependencies.
- Provide insights into geographical revenue distribution.

The dashboard delivers actionable insights to optimize sales strategies and market focus.

---

## Key Insights
### **[1] Revenue Trend Analysis**
- **Seasonality Observed**: Revenue remains stable for the first **8 months** (~$685K/month).
- **Sales Surge in Q4**:
  - **September**: 40% increase in revenue compared to August.
  - **November**: Peak revenue of **$1.5M**.
  - **December**: Incomplete data, limiting conclusive analysis.
- **Conclusion**: Sales exhibit strong seasonality, with a significant boost in the last **4 months** of the year.

### **[2] Growth Opportunities by Country**
- The UK is excluded as it already has high demand.
- **Top 4 growth markets**:
  - **Netherlands**
  - **Ireland**
  - **Germany**
  - **France**
- These countries show high unit sales and revenue, warranting further market investment.

### **[3] Top 10 Customers Analysis**
- The top **10 customers** exhibit **similar purchasing patterns**.
- The **highest revenue-generating customer** only spends **17% more** than the second highest.
- **Conclusion**: Revenue is **not dependent on a few key customers**, indicating a **balanced customer base** with **low bargaining power**.

### **[4] Geographical Revenue Distribution**
The map visual reveals:
- **High-revenue regions**: UK, Netherlands, Ireland, Germany, France, Australia.
- **Low-revenue regions**: North America has minimal sales.
- **No demand observed** in **Africa, Asia, and Russia**.
- **Recommendation**: A new strategy should target underperforming regions to boost revenue and profitability.

---
## Dashboard Design 
![image](https://github.com/user-attachments/assets/a8fff5f5-8001-45b1-8cda-97aa6284a6a0)


## Steps Followed
### **Data Preparation**
1. **Dataset loaded into Power BI Desktop**.
2. **Power Query Editor used for data cleaning**:
   - Removed records with **negative quantities and unit prices**.
   - Ensured **error-free dataset** before analysis.

### **Dashboard Design**
1. Created KPIs for **Revenue Trends, Top Countries, and Customer Insights**.
2. Designed the following visuals:
   - **Line chart** for **Revenue Trends by Month**.
   - **Bar chart** for **Top 10 Countries by Sales & Revenue**.
   - **Table** for **Top 10 Customers & Purchase Volume**.
   - **Map Chart** for **Geographical Revenue Distribution**.
3. Applied a professional theme for a visually engaging design.

### **Interactivity**
1. Added slicers for dynamic filtering by:
   - **Country**
   - **Time Period**
   - **Customer Segment**
2. Linked visuals for **cross-filtering and deeper insights**.

---

## Tools Used
- **Power BI Desktop**: For designing the dashboard.
- **Dataset**: Retail store sales data (post-cleaning & transformation).

---

## How to Use
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Tmuley/Online-Retail-store.git


# Conclusion
The Retail Store Sales Analytics Dashboard provides valuable insights into seasonal revenue patterns, high-potential markets, and customer purchasing behavior. The findings suggest strategic investments in European markets and an expansion strategy for untapped regions to drive growth and profitability.
