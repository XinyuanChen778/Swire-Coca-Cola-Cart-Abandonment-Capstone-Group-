# Cart Abandonment Analytics

- Swire Coca Cola Capstone Project
- Group 3: Xinyuan Chen, Linh Do, Mike Hanger

## 1. Project Summary

This project examines why customers place items in their MyCoke360 cart but do not complete their order by their assigned re order date. Cart abandonment creates lost revenue, disrupts delivery planning, and reduces digital engagement.

We combined Google Analytics, orders, and sales data to identify the key behaviors that lead to abandonment. We also built predictive models to estimate the likelihood of missed orders and to help Swire design proactive recovery strategies. The business problem and success metrics were defined by Swire Coca Cola and focus on revenue retention and operational efficiency. 

## 2. Business Value

### 2.1 Clear Drivers of Abandonment

Our analysis revealed several consistent patterns that contribute to abandonment.
- Lack of checkout activity
- Heavy browsing with no follow up
- Higher abandonment on tablet and mobile devices
- Higher abandonment for customers with longer order frequencies
- Product patterns such as large packs or specialty items

These findings come from the customer and behavior insights in the project presentation. 

### 2.2 Predictive Modeling

We created two complementary models. The window level model predicts abandonment within a specific order cycle and reached AUC values up to 0.95. The customer level model identifies customers with repeated unstable behavior and reached an AUC of 0.868. These models help Swire identify risk earlier and support more reliable ordering behavior.


### 2.3 Actionable Recommendations

We provide a set of targeted strategies to support order consistency and reduce cart abandonment. These include guiding chronic abandoners, improving reminders based on order schedules, recommending relevant product bundles, and offering support for consistently unstable customers. These ideas align closely with the project scope and intended business outcomes. 

## 3. Data Sources

The project integrates multiple data sources including Google Analytics events, customer tables, material information, visit plans, operating hours, orders, and sales. This combination provides a complete view of customer behavior and order outcomes across windows. The structure and definitions come from the technical documentation. 

## 4. Repository Contents

The main analysis and models are contained in the EDA_Group3 file, which includes data processing, exploratory insights, and predictive modeling. The repository also includes figures used for analysis and the final project presentation.

## 6. How to Use This Repository

Begin with the EDA_Group3 file to understand the full workflow from data preparation to modeling. Review the figures for key charts and patterns. Use the final presentation for a concise summary of business impact and recommendations.
