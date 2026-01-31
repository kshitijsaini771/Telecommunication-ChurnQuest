
# Telecommunication-ChurnQuest

<!--![Churn](http://raw.githubusercontent.com/PratyushPuri/Telecommunication-ChurnQuest/refs/heads/main/ChurnQuest%20Dash.png)-->

<div align="center">

<img src="bank.jpeg" alt="drawing" width="500"/>

</div>


## Project Overview

This project looks at customer churn patterns at a top telecommunications company, to find out what causes customers to leave. By studying customer behavior, usage patterns, and service interactions, this analysis offers valuable insights to create targeted retention strategies and improve customer satisfaction.

## Dataset Information

This analysis uses the [Kaggle Customer Churn Prediction 2020 dataset](https://www.kaggle.com/competitions/customer-churn-prediction-2020/data). It simulates customer behavior for a telecommunications company based in the U.S. The dataset has **5,000 customer records** with **20 features**. It is designed to predict whether a customer will leave the service (churn).

- **Source**: Kaggle competition dataset tailored for modeling customer churn in the telecom industry.
- **Time Coverage**: Cross-sectional (snapshot of customer accounts at one point in time).
- **Key Variables**:
  - **Target**: `churn` (binary: "yes"/"no") indicates if the customer left the provider.
  - **Customer Profile**: `state` (2-letter U.S. state code), `account_length` (months with provider), `area_code`.
  - **Service Plans**: `international_plan` (yes/no), `voice_mail_plan` (yes/no).
  - **Call Usage**:
    - **Day**: `total_day_minutes`, `total_day_calls`, `total_day_charge`
    - **Evening**: `total_eve_minutes`, `total_eve_calls`, `total_eve_charge`
    - **Night**: `total_night_minutes`, `total_night_calls`, `total_night_charge`
    - **International**: `total_intl_minutes`, `total_intl_calls`, `total_intl_charge`
  - **Engagement Metrics**: `number_vmail_messages`, `number_customer_service_calls`.
- **Notes**:
  - All monetary values are in USD.
  - `area_code` is given as a string (e.g., "area_code_415") but can be converted to real area codes if necessary.
  - The dataset is synthetic but modeled after real telecom churn patterns, making it suitable for classification and business insight analysis.

## Analysis

> Solution File is `ChurnQuest.xlsx`

To understand what causes customers to leave, we carried out a structured analysis:

**Analysis and Insights:**
*   Measured the **overall churn rate and volume** to establish the scale of the problem.
*   Compared churned customers to retained customers across key metrics like **account duration, service calls, and call charges (day/evening/night/international)**.
*   Studied how **service plan subscriptions** (e.g., International Plan, Voicemail Plan) affect the likelihood of churn.
*   Looked into connections between **usage patterns** (total minutes, number of calls) and customer departure.
*   Carried out **segmented analysis by Area Code** to find geographic areas with high churn.
*   Explored interaction effects, such as how **international call charges** specifically impact churn for international plan subscribers.
*   Investigated thresholds, like whether **customer service calls exceeding 3** significantly raise churn risk.
*   Conducted **cluster analysis** to identify different customer groups based on their usage patterns and related churn rates.
*   Analyzed the relationship between **account length quartiles** and churn to see if newer customers are more at risk.

This thorough approach moved from broad metrics to detailed segments. It uncovered not just *if* customers leave, but also *which* customers leave, *when*, and under *what* service conditions. The findings directly inform targeted retention strategies.

## **Dashboard Overview: Telecom Customer Churn**

This interactive dashboard gives a clear view of customer loss, highlighting important metrics and trends.

**Key Performance Indicators (KPIs):**
*   **Churn Rate:** The main metric shows that **14.07%** of customers have left.
*   **Average Account Tenure:** The average customer stays for **100.24 months** (about 8.35 years).
*   **Average Service Calls:** Customers make an average of **1.56 calls** to customer service.
*   **International Plan Adoption:** Shows the percentage of customers with international calling plans.

**Main Visualizations:**
*   **Top 10 States by Churn:** A geographic breakdown showing regions with the highest loss rates for targeted action.
*   **Overall Churn Status:** A pie or donut chart that clearly visualizes the split between churned and active customers.
*   **International Adoption Analysis:** Looks at how international plan subscriptions relate to churn behavior.
*   **Churn by Service Calls:** A chart that shows how the chance of churn increases with more customer service calls.

**Interactivity:**
*   Use the **Churn (Yes/No) slicer** to filter the whole dashboard. You can view data only for churned customers to analyze their profile or for retained customers to understand what keeps them.

![Churn](ChurnQuest%20Das.png)

## **How to Use the Dashboard**

This interactive dashboard offers a simple way to analyze customer attrition. Follow these steps to explore the data:

1.  **Open the File:** Launch the `ChurnQuest.xlsx` file in Microsoft Excel.

2.  **Navigate & Interact:**
    *   **Review KPIs:** Start by looking at the Key Performance Indicators (KPIs) at the top. Check the overall **Churn Rate (14.07%)** and the **Average Account Duration**.
    *   **Use the Slicer:** Use the main **Churn (Yes/No)** slicer to filter the entire dashboard. Select "Yes" to analyze the profile of customers who left or "No" to focus on active customers and retention factors.
    *   **Analyze Charts:** Click on or hover over charts, like **Top 10 States by Churn** or **Churn by Customer Service Calls**, to see exact values and observe patterns.

3.  **Refresh Data (If Applicable):**
    *   If the dashboard is linked to an updated dataset, refresh it by going to the **Data** tab in Excel and selecting **"Refresh All."**
    *   **Security Note:** If asked to enable macros or external content, choose "Enable" only if you trust the file's source and security.

## Author & Contact
- Name: `Kshitij Saini`
/ [LinkedIn](https://www.linkedin.com/in/kshitij-saini-b950b7299?utm_source=share_via&utm_content=profile&utm_medium=member_android)

    
