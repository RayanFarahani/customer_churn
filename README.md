# 📊 Telecom Customer Churn Analysis

This project analyzes customer churn for a telecommunications company using structured dashboard reporting and data-driven insights.

## Objective

The objective is straightforward:

- Measure overall churn  
- Identify the strongest churn drivers  
- Highlight actionable retention strategies  

---

# 📁 Dataset Summary

- **Total Customers:** 6,687  
- **Churned Customers:** 1,796  
- **Overall Churn Rate:** 26.86%  

### Dataset Includes:

- Demographics (Age, Senior flag, Gender)  
- Contract Type  
- Payment Method  
- Account Length (months)  
- Customer Service Calls  
- State  
- Data Consumption (GB)  
- Unlimited Data Plan  
- Extra International Charges  
- Extra Data Charges  
- Group Size  
- Churn Category & Churn Reason  

---

# 📌 Dashboard Analysis

## 1️⃣ Overview Page

### Key KPIs

| Metric | Value |
|--------|--------|
| Customers | 6,687 |
| Churned Customers | 1,796 |
| Churn Rate | 26.86% |

Approximately **1 in 4 customers churned**, indicating significant retention opportunity.

---

### Churn Category Breakdown

| Category | Share of Churn |
|-----------|----------------|
| Competitor | 44.8% |
| Attitude | 16.0% |
| Dissatisfaction | 15.9% |
| Price | 11.1% |
| Other | 10.6% |

Nearly half of churn is competitor-related. However, over **30% is tied directly to service experience and dissatisfaction**, which are controllable internally.

---

### Top Churn Reasons

- Competitor made better offer (16.9%)  
- Competitor had better devices (16.5%)  
- Attitude of support person (11.3%)  
- Competitor offered more data (6.1%)  
- Competitor offered higher download speeds (5.3%)  
- Price too high (4.1%)  
- Network reliability (3.8%)  

Customers are primarily leaving for perceived value differences.

---

### Contract Type Distribution

| Contract Type | Customer Share | Churn Rate |
|---------------|----------------|------------|
| Month-to-Month | 51% | 46.3% |
| One Year | 22% | 11.3% |
| Two Year | 27% | 2.8% |

Month-to-Month contracts represent **87.9% of all churned customers**.

This is the strongest structural churn driver in the dataset.

---

### Geographic Insights

- California shows the highest churn rate (~63%), significantly above the average.  
- Several other states cluster around 30–35%.

Regional competitive pressure may be influencing churn.

---

## 2️⃣ Age Groups, Payments & Contracts

### Churn by Age Group

| Age Group | Churn Rate |
|------------|------------|
| Under 30 | 23.0% |
| 30–64 | 24.7% |
| Senior | 38.2% |

Senior customers churn at a substantially higher rate.

---

### Account Length Impact

- **Average tenure (Churned):** 18 months  
- **Average tenure (Retained):** 37 months  

Churn risk is highest in early customer lifecycle stages.

---

### Payment Method Impact

| Payment Method | Churn Rate |
|----------------|------------|
| Paper Check | 38.0% |
| Direct Debit | 34.5% |
| Credit Card | 14.5% |

When combined with Month-to-Month contracts, churn exceeds 50%.

---

### Group Size Effect

| Customers in Group | Churn Rate |
|--------------------|------------|
| 0 (No group) | 32.9% |
| 2–6 customers | 5–8% |

Group/family plans significantly reduce churn.

---

## 3️⃣ Usage & Unlimited Plan Analysis

### Consumption vs Unlimited Plan

| Usage | Unlimited Plan | Churn Rate |
|--------|---------------|------------|
| < 5GB | Yes | 34.7% |
| < 5GB | No | 12.3% |
| 5–10GB | Yes | 33.6% |
| 10+GB | Yes | 27.7% |

Customers using less than 5GB but paying for Unlimited churn at nearly 35%.

This indicates a plan-value mismatch.

---

### Extra Data Charges

Among non-unlimited customers:

- With extra data charges → ~33% churn  
- Without extra data charges → ~8% churn  

Overage charges strongly correlate with churn.

---

## 4️⃣ Insights Page

### Customer Service Calls — Strongest Churn Predictor

| Service Calls | Churn Rate |
|---------------|------------|
| 0 | 8.9% |
| 1 | 31.3% |
| 2 | 36.6% |
| 3 | 87.5% |
| 4 | 99.7% |
| 5 | 100% |

Customers with **3+ service calls are almost guaranteed to churn**.

This is the most actionable operational signal.

---

# 🎯 Key Churn Drivers (Ranked)

1. Customer service friction  
2. Month-to-Month contracts  
3. Plan mismatch (Low usage + Unlimited)  
4. Competitive offers & devices  
5. Senior customer segment  
6. Overage data charges  

---

# 🚀 Business Recommendations

## 1. Reduce Month-to-Month Exposure

- Incentivize conversion to 1-year or 2-year contracts  
- Target high-risk monthly customers  

## 2. Implement Service Call Escalation

- Flag customers after 2 calls  
- Escalate aggressively at 3 calls  

## 3. Right-Size Unlimited Plans

- Identify low-usage Unlimited customers  
- Offer lower-tier alternatives before churn occurs  

## 4. Expand Group Plans

Group accounts reduce churn from ~33% to ~6%.

## 5. Minimize Overage Shock

- Real-time usage alerts  
- Auto plan recommendations  

---

# 🧠 Tools Used

- Python (Pandas, NumPy)  
- Power BI (Dashboard development)  
- Data cleaning and exploratory analysis  

---

# 📌 Conclusion

Churn in this telecom dataset is concentrated and predictable.

The highest impact levers are:

- Contract structure  
- Customer service interactions  
- Plan-value alignment  
- Competitive positioning  

Addressing these areas can significantly reduce churn and improve long-term customer retention.
