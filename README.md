# Bank Customer Churn Analysis
This repository contains a comprehensive bank customer churn analysis, encompassing the entire analytics workflow from data cleaning and preparation to exploratory data analysis (EDA), dashboard development in Power BI, and actionable business recommendations. 

## Project Overview

Customer churn is a major challenge in the banking industry, as losing customers directly impacts revenue and long-term growth. This project presents an end-to-end customer churn analysis aimed at identifying the key factors that influence customer attrition and providing actionable insights to improve customer retention.

This project covers the entire data analytics lifecycle, from data cleaning and preparation to exploratory analysis, visualization, and business recommendations.

## Project Objectives

* Measure the overall customer churn rate

* Identify customer segments with high churn risk

* Analyze the impact of demographics, financial behavior, and engagement on churn

* Provide data-driven recommendations to reduce customer attrition

## Dataset Description

The dataset contains information on 10,000 bank customers, including:

* Customer demographics (Age, Gender, Geography)

* Financial attributes (Balance, Estimated Salary, Credit Score)

* Product ownership (Number of Products)

* Engagement metrics (Tenure, Activity Status)

* Customer experience indicators (Satisfaction Score)

* Churn status (0/1)

Note: The dataset was provided in a raw format and required cleaning and transformation before analysis.

## Tools & Technologies

* Power Query – Data cleaning and preprocessing (Transformation)

* Power BI – Data modeling, analysis, and dashboard development

* DAX – Calculated measures and KPIs

## Data Cleaning & Preparation

The data cleaning process was performed using Power Query to ensure accuracy and consistency.

* Key Data Cleaning Steps

* Removed duplicate records to avoid double-counting customers

* Checked for missing values and handled them appropriately

* Standardized column names and data formats

* Verified data types for numerical and categorical fields

**Created derived columns such as:**

* Churn Status (Churned representing 1 / Not Churned representing 0)

* Customer Activity Category (Active representing 1 / Inactive representing 0)

Table Sample

<img width="1325" height="525" alt="Data Clearng   Transformation(Sample 1)" src="https://github.com/user-attachments/assets/447fd04d-8e2c-48b9-8275-6231a40e2eef" />

<img width="1324" height="519" alt="Data Cleaning   Transformation (Sample 2)" src="https://github.com/user-attachments/assets/55d3aeec-dd52-4ea6-8559-382f209c68b3" />

## Data Modeling

After cleaning, the dataset was imported into Power BI for modeling and analysis.

Modeling Approach: I established a single fact table structure

<img width="916" height="520" alt="image" src="https://github.com/user-attachments/assets/bd33c67d-efd8-48a8-863b-7c531278f898" />


## DAX Measures

I created calculated measures using DAX, including:

* Total Customers

* Churned Customers

* Churn Rate

* Active & Inactive Customers

<img width="641" height="166" alt="Screenshot 2026-01-23 001317" src="https://github.com/user-attachments/assets/56e9b595-0ad3-400f-9b10-e528211d9d5b" />

## Exploratory Data Analysis (EDA)

An exploratory analysis was conducted to understand patterns, distributions, and relationships between variables.

Key Areas Explored

* Churn distribution across gender and age groups

* Churn by geographic location

* Impact of account balance and salary on churn

* Relationship between product ownership and churn

* Effect of tenure and activity status on churn

Insights from EDA guided the final dashboard design and storytelling approach.

## Dashboard Development

Three interactive dashboards were built in Power BI to present insights clearly and efficiently.

Dashboard 1: Churn Overview & Customer Profile

This dashboard provides a high-level view of customer churn and key demographic patterns.

<img width="911" height="518" alt="Page 1" src="https://github.com/user-attachments/assets/84b32f1a-a3b2-46b7-8ed4-dc4b17054f12" />

## Key Metrics from the dashboard

* Total Customers: 10,000

* Churned Customers: 2,038

* Churn Rate: 20.38%

* Active Customers: 5,151

* Inactive Customers: 4,849

## Key Insights

* Inactive customers have a significantly higher churn rate

* Customers with only one product are more likely to churn

* Churn varies across regions, with some locations experiencing higher attrition

* Middle-aged customers show higher churn concentration

Dashboard 2: Customer Behavior & Financial Profile

This dashboard focuses on customer behavior, financial attributes, and experience indicators.

<img width="915" height="519" alt="Page 2" src="https://github.com/user-attachments/assets/2cfe8633-be1a-4402-825c-29cfde49b716" />

## Key Metrics from the dashboard

* Average Credit Score: 650.53

* Average Account Balance: $76.49K

* Average Salary: $100.09K

* Average Age: 38.92 years

## Key Insights

* Customer satisfaction strongly influences churn

* Salary level alone does not prevent churn

* Customers with multiple products are more likely to remain loyal

* New customers (0–2 years tenure) are more likely to churn

Dashboard 3: Executive Summary

<img width="910" height="519" alt="Page 3" src="https://github.com/user-attachments/assets/035c2e1f-5678-42a4-b077-ee4a6a5efc62" />

## Overall Findings

* The overall churn rate is 20.38%

* Customer inactivity is a major churn driver

* Product engagement significantly reduces churn risk

* Customer satisfaction is more influential than income level

* Early-stage customers are the most vulnerable to churn

## Recommendations

Based on the analysis, the following actions are recommended:

* Re-engage Inactive Customers by targeting inactive users with personalized offers and reminders.

* Increase Product Adoption by encouraging customers with a single product to adopt additional services.

* Improve Customer Experience by actively monitoring satisfaction scores and addressing issues proactively.

* Strengthen Early Customer Onboarding by implementing loyalty programs and onboarding support for new customers.

* Apply regional retention strategies through efforts tailored to specific regional churn patterns.

## Conclusion

This project analyzed bank customer churn using demographic, financial, and behavioral data to identify the key drivers of customer attrition. The analysis revealed an overall churn rate of 20.38%, with churn primarily driven by low customer engagement, inactivity, limited product ownership, and poor customer satisfaction, rather than financial capacity, such as salary.

Inactive customers and those holding only one product exhibited significantly higher churn rates, while customers with multiple products and higher satisfaction scores were more likely to remain loyal. Additionally, newer customers were found to be more vulnerable to churn, highlighting the importance of early-stage engagement and onboarding. Geographic differences in churn further suggest the need for region-specific retention strategies.

Overall, the findings demonstrate that customer experience and engagement are the most critical factors influencing churn. By focusing on improving customer activity, satisfaction, product adoption, and early relationship management, banks can effectively reduce customer attrition and enhance long-term customer value.

This analysis identifies the key drivers of bank customer churn, showing that engagement and customer experience have a greater impact than financial factors. The insights enable targeted retention strategies that can reduce churn, improve customer lifetime value, and support more effective, data-driven decision-making.

🔗 [Link to the PowerPoint Slide Report](https://docs.google.com/presentation/d/1PUCP3OWMmNBXHllhe3my1h2vJXYV6Vtj/edit?usp=drive_link&ouid=110710168789266265367&rtpof=true&sd=true)

### Analysis By:
Ibrahim Abdulrasaq | Data Analyst & BI Analyst

Connect with Me 👇

🔗 [Email](ibrahimabdulrasaqademola2017@gmail.com)

🔗 [linkedin](https://github.com/ibrahimabdulrasaq)

🔗 [Github](https://github.com/ibrahimabdulrasaq)
