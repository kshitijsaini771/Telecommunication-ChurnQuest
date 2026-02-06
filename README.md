# Telecom Customer Churn Analytics

## Problem Statement
Telecom providers operate in a highly competitive market where losing subscribers directly impacts revenue and growth. This project analyzes customer churn patterns for a U.S.-based telecom company to **identify who is likely to leave, why they churn, and under which service conditions**, enabling targeted retention strategies and better customer experience management.

---

## Analysis Done
- Used the **Customer Churn Prediction 2020** dataset (5,000 customers, 20 features) to study churn behavior across demographics, service plans, and usage patterns.
- Quantified the **overall churn rate** and number of churned customers to assess the scale of the problem.
- Compared churned vs. retained customers across:
  - **Account length (tenure)**
  - **Number of customer service calls**
  - **Call minutes and charges** for day, evening, night, and international segments.
- Evaluated how **International Plan** and **Voicemail Plan** enrollment influences churn probability.
- Analyzed **usage behavior**:
  - Total minutes, call counts, and charges.
  - Whether heavy call or charge patterns increase churn risk, especially for international usage.
- Performed **geographic segmentation** by area code to detect regions with higher churn.
- Examined interaction effects, such as:
  - Impact of **high international charges** on customers with and without an International Plan.
  - The churn spike among customers making **3+ customer service calls**, indicating dissatisfaction.
- Applied **cluster analysis** to group customers by usage and engagement profiles, then compared churn rates across clusters.
- Studied churn across **account length quartiles** to see if newer, mid-tenure, or long-term customers are more at risk.

---

## Dashboard Overview
> To use the dashboard, open `Solution.xlsx` and navigate to the **“Dashboard”** sheet. All interactive elements work only on this tab.

The Excel dashboard presents a concise, executive-level view of churn performance and drivers:

- **Key metrics:**
  - Overall churn rate: **14.07%**
  - Average account length: **100.24 months**
  - Average customer service calls: **1.56 per customer**
- **Geographic churn hotspots:**
  - Bar chart of **Top 10 churn states**, with **West Virginia (WV)** leading at 139 churned customers.
- **Churn status summary:**
  - Donut chart showing **86% retained vs. 14% churned** customers.
- **Plan impact:**
  - Visual comparing churn across **International Plan vs. No International Plan**, showing higher churn among customers **without** the plan.
- **Service experience:**
  - Churn by **customer service calls**, with a clear jump in churn risk when customers make **3 or more** calls.
- Designed for **leadership, retention, and customer success teams** to prioritize at-risk segments, refine plan offerings, and optimize support processes.

![Telecom Churn Dashboard](Capture.PNG)

---

## Recommendations
- **Prioritize high-risk segments:** Target customers with high customer service call frequency, shorter tenure, and high international usage for proactive outreach.
- **Improve service experience:** Reduce friction in customer support workflows, emphasizing fast resolution for customers who contact support multiple times.
- **Optimize plan design:** Promote or adjust **International Plans** for heavy international users to reduce bill shock and perceived unfair pricing.
- **Launch targeted retention campaigns:** Use geographic and usage-based segments (e.g., high-churn states, heavy callers) for tailored offers and loyalty incentives.
- **Monitor churn KPIs regularly:** Integrate this dashboard into monthly reviews to track churn trends, evaluate retention initiatives, and refine strategy iteratively.

---

**Author:** `Kshitij Saini`  
**LinkedIn:** [Kshitij Saini](https://www.linkedin.com/in/kshitijsaini-b950b7299?utm_source=share_via&utm_content=profile&utm_medium=member_android)
