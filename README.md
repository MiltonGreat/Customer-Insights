# Analyzing Customer Spending Habits - Tableau Dashboard

### Overview

This project analyzes customer behavior and preferences using demographic and transactional data. The primary objective is to understand customer experience and purchasing trends to uncover actionable insights for business decision-making. The data includes information on customer age, gender, revenue, quantity, and purchase history.

The goal is the clean and prepare data to build visualizations (dashboard) using Tableau.

### Workflow

##### 1. Data Cleaning and Processing:
- Handled missing values for critical fields (Date, Customer Age, and Revenue).
- Converted the Date column to a datetime format for better time-based analysis.
- Created new features: (1) Customer Segment: Categorized customers into age groups (<25, 25-40, 40-60, 60+). (2) Total Purchase Value: Calculated revenue for each transaction.
- Aggregated data by customer segment, gender, and date for deeper insights.

##### 2. Data Export:
- Saved the cleaned and processed dataset (processed_customer_spending_data.csv) for visualization in Tableau.

##### 3. Interactive Dashboard:
- Total revenue by customer segment.
- Purchase trends over time.
- Average purchase value by gender and age group.
- Key demographic insights (e.g., average age of customers in different segments).

### Future Improvements

- Include clustering analysis to identify distinct customer groups.
- Perform predictive modeling to forecast customer lifetime value (CLV).
- Add dynamic filters in Tableau for deeper interactivity.

### Source

https://www.kaggle.com/datasets/thedevastator/analyzing-customer-spending-habits-to-improve-sa
