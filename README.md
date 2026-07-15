# Data-analysis-for-marketing-strategy

## Project Overview
This project delves into e-commerce customer behavior to craft data-driven marketing strategies. By analyzing customer demographics, spending patterns, satisfaction, and purchase recency, we aim to optimize customer segmentation, refine promotional efforts, and enhance retention campaigns. The insights gained are designed to empower marketing teams with actionable recommendations.

## Dataset
The analysis utilizes the `E-commerce Customer Behavior - Sheet1-selected-columns.csv` dataset sourced from [Kaggle](https://www.kaggle.com/datasets/uom190346a/e-commerce-customer-behavior-dataset).
Key features include:

*   **Customer ID**: Unique identifier.
*   **Gender, Age, City**: Demographic information.
*   **Membership Type**: Customer loyalty status.
*   **Total Spend, Items Purchased**: Transactional behavior.
*   **Average Rating**: Customer satisfaction metric.
*   **Discount Applied**: Indicates if a discount was part of the purchase.
*   **Days Since Last Purchase**: Recency of customer activity.


## Marketing Strategy Driven by Data Analysis

### 1. Customer Segmentation

*   **Objective**: To group customers into distinct segments based on their behavior and characteristics.
*   **Methodology**: K-Means clustering applied to 'Age', 'Total Spend', and 'Days Since Last Purchase' after feature scaling. This helps identify different customer personas.
*   **Marketing Impact**: Enables highly targeted marketing campaigns by understanding the unique needs and value of each segment (e.g., high-value, price-sensitive, or at-risk customers).

### 2. Promotional Strategy Optimization

*   **Objective**: To evaluate the effectiveness of discounts and recommend a data-backed promotion approach.
*   **Methodology**: Comparative analysis of 'Total Spend' and 'Items Purchased' between transactions with and without applied discounts.
*   **Marketing Impact**: Provides clear guidance on whether to continue, modify, or discontinue general discount strategies, suggesting alternatives like value-added promotions (e.g., 'buy one get one free') to boost sales without eroding profit margins.

### 3. Customer Retention Strategies

*   **Objective**: To identify customers at risk of churning and implement proactive retention measures.
*   **Methodology**: Customers are categorized into 'Safe', 'Churn Risk', or 'Critical' based on 'Days Since Last Purchase'. Specific 'Retention Actions' are then assigned to each risk level.
*   **Marketing Impact**: Allows for timely and tailored interventions, from gentle nurturing for 'Safe' customers to aggressive win-back campaigns for 'Critical' customers, thereby reducing churn and increasing customer lifetime value.

## How to Leverage this Analysis

1.  **Understand Customer Profiles**: Use the cluster analysis to create detailed personas for your target audience.
2.  **Refine Promotion Campaigns**: Implement the recommended promotional adjustments to maximize sales effectiveness and profitability.
3.  **Proactive Retention**: Integrate the defined retention actions into your CRM and marketing automation systems to engage customers at critical points.
4.  **Continuous Monitoring**: Regularly review the impact of these strategies and iterate based on new data to ensure sustained growth and customer loyalty.
