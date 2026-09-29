# Netflix Customer Churn Analysis Dashboard

## Project Overview
This Power BI dashboard analyzes customer churn patterns for a Netflix dataset of **5,000 customers**. The primary goal is to identify high-risk subscriber segments, analyze engagement metrics driving cancellation, and provide actionable business recommendations to reduce overall churn and protect recurring revenue.

---

## Executive Summary & Visuals

### 1. Overview Dashboard
Provides high-level KPIs across the user base, tracking total revenue, churn metrics, and average customer watch hours.

![Netflix Customer Churn Overview](overview.png)

* **Total Customers:** 5,000
* **Churn Rate:** 50.3%
* **Total Revenue:** $68.4K
* **Average Watch Hours:** 11.65 hours
* **Customer Distribution:** 493 churned vs. 507 active

---

### 2. Segment Analysis
Breaks down churn rates by specific user dimensions: subscription plan, geographical region, and primary viewing device.

![Churn Rate by Customer Segment](segment_analysis.png)

* **Churn by Subscription:** Basic plan leads at **61% churn rate**.
* **Churn by Region:** Africa exhibits the highest regional churn at **58%**.
* **Churn by Device:** Laptop users show the highest device-based churn at **55%**.

---

### 3. Usage vs. Churn Analysis
Examines behavioral patterns and engagement triggers behind customer cancellations.

![Engagement Patterns Behind Churn](usage_vs_churn.png)

* **Watch Hours vs. Days Since Last Login:** Churned users cluster heavily in low usage volume and high inactivity timeframes.
* **Average Last Login (Active Users):** 9 days
* **Average Last Login (Churned Users):** 42 days

---

## Key Data Insights

1. **High-Risk Segment Profile:** Customers on the **Basic plan** residing in **Africa** and streaming primarily via **laptop** demonstrate the highest risk of churn.
2. **Engagement Threshold:** Active subscribers log in within an average of **9 days**, whereas subscribers who go inactive for **40+ days** have a significantly higher probability of churning.
3. **Plan Friction:** The Basic tier's high churn rate (61%) suggests potential user friction regarding feature constraints relative to Standard and Premium options.

---

## Recommended Action Strategy

* **Early Warning Inactivity Triggers:** Set up automated re-engagement campaigns when a subscriber reaches 14 consecutive days of inactivity.
* **Targeted Regional Strategy:** Investigate infrastructure, localized pricing options, or streaming quality tailored to users in the African market.
* **Basic Tier Value Optimization:** Assess features offered in the Basic plan to improve subscriber retention and encourage upgrades to higher tiers.
