# Target Business Case Study

## Project Overview
This project analyzes **e-commerce customer behavior and operations in Brazil** using SQL queries on Google BigQuery. The aim is to uncover insights into order trends, customer demographics, delivery times, payments, and revenue growth to guide data-driven decisions for business expansion and operational efficiency.

---

## Motivation
E-commerce businesses rely on understanding customer behavior, seasonality, delivery efficiency, and payment preferences. This project provides actionable insights to optimize logistics, improve customer retention, and enhance overall profitability.

---

## Dataset
- **Source:** Target Business Case Dataset (BigQuery: `scaler-dsml-sql-396515.target_business_case`)
- **Tables Used:** `customers`, `orders`, `order_items`, `payments`
- **Period:** 4th September 2016 – 17th October 2018
- **Region:** Brazil

---

## Methodology
1. **EDA & Data Understanding**
   - Analyzed table structures and column data types.
   - Identified order date ranges and customer distributions.

2. **Trend & Seasonality**
   - Order volume and revenue growth year-over-year.
   - Seasonal demand patterns (spikes during Carnival season).
   - Purchase behavior by time of day (afternoon & night most active).

3. **Geographic Insights**
   - State-level customer and order distribution (SP & RJ dominate).
   - Monthly state-wise order trends.

4. **Economic Impact**
   - % increase in revenue (2017 → 2018).
   - State-level total & average order price and freight charges.

5. **Delivery & Logistics**
   - Actual vs. estimated delivery times.
   - Top 5 states with fastest and slowest deliveries.
   - Positive correlation between freight value and delivery delays.

6. **Payment Analysis**
   - Payment types: Credit card (most common), debit card (least used).
   - Installments: Majority single-installment orders; maximum observed = 24.

---

## Results & Insights
- **Growth:** E-commerce orders in Brazil rose steadily from 2016–2018.
- **Seasonality:** Demand spikes in February–March (Carnival).
- **Customer Habits:** Most purchases occur in the afternoon/evening.
- **Logistics:** São Paulo has lowest average delivery time; Roraima highest freight costs and delays.
- **Payments:** Credit cards dominate and are growing fastest.

---

## Actionable Recommendations
- Optimize logistics in high-delay regions to improve delivery speed.
- Expand market penetration in underperforming states outside SP/RJ.
- Launch seasonal campaigns during Carnival & holiday periods.
- Implement loyalty programs, referral incentives, and chat support services.
- Reassess freight pricing to balance competitiveness and profitability.
