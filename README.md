# Banking Customer Churn Analysis

## Project Overview:

The bank is facing a growing issue of customer churn, where clients are closing their accounts or reducing engagement with banking products and services. This trend not only leads to a direct loss of revenue but also increases the cost burden of acquiring new customers to replace those lost. Despite ongoing retention efforts, the lack of a data-driven understanding of why customers leave has made it difficult to intervene effectively.

The primary objective of this project is to uncover patterns and factors that contribute to churn by analyzing customer demographics, behavior, and product usage. These insights will help the bank proactively identify at-risk customers and design targeted strategies to improve retention, enhance customer satisfaction, and protect long-term profitability.

### Data Structure and Initial Checks:

The bank's database structure consists of a table Customer_Churn_Dataset with a total row count of 10,000 records.

Prior to beginning the analysis, a variety of checks were conducted for quality control and familiarization with the datasets using Python.

### Data Quality Check:

-	Check Null values
-	Check Duplicates
-	Deleting irrelevant columns  

## Executive Summary:

### Overview of Findings:

The **overall customer churn** percentage was **20.4%**. The **key factors** that significantly impacted customer churn are **Number of Products availed by customer, Age, Inactivity, Geography and Gender**. Churn rate of France and Spain are comparable almost 16% while **Churn rate of Germany is almost twice** around **32%**. **Female customers are more likely to churn** around 25% which is 9% higher than Male churn rate. The **mean age of churned customers** is around **45 yrs**. **Inactive customers are more likely to churn** around 13% which twice of that of Active customers.

![Overall Churn](https://github.com/Curious-Creative-Mind/Banking-Customer-Churn-Analysis/blob/main/Churn.png?raw=true)

Below is the detailed analysis of various factors that may impact customer churn.

### Geography

- Customers from France are almost twice of that from Spain and Germany.
- Despite having similar customer base in Spain and Germany, churn rate in Germany is almost twice of that of Spain.
- Churn rate of France and Spain are comparable almost 16% while Churn rate of Germany is almost twice around 32%.

![Churn Geography](https://github.com/Curious-Creative-Mind/Banking-Customer-Churn-Analysis/blob/main/Churn%20Geography.png?raw=true)

### Gender

- Despite Male customers being slightly higher than Female customers by 10%, churn rate of female customer is around 25% while that of male is 16% which is 9% higher than male churn rate.

![Churn Gender](https://github.com/Curious-Creative-Mind/Banking-Customer-Churn-Analysis/blob/main/Churn%20Gender.png?raw=true)

### Age

- Most customers are middle aged belonging to the age group of 30-50 yrs.
- The mean age of churned customers is around 45 yrs while most of them lie in the age bucket of 38-50 yrs.

![Churn Age](https://github.com/Curious-Creative-Mind/Banking-Customer-Churn-Analysis/blob/main/Churn%20Age.png?raw=true)

### Bank Balance

- Huge no. of customers around 32% have 0 or very low account balance. These customers are slighly less likely to churn as compared to those who have significant balance.
- Around 15% of low balance customers churned while 22% of customers with medium to high account balance churned.
- 23% of churned customers belonged to low balance category.
- Thus Bank Balance doesn't have significant impact on customer churn.

![Churn Balance](https://github.com/Curious-Creative-Mind/Banking-Customer-Churn-Analysis/blob/main/Churn%20Balance.png?raw=true)

### Estimated Salary

- Customers seem to be evenly distributed across estimated Salary ranges and so is their churn rate.
- Estimated Salary doesn't seems to have any significant impact on customer churn.

![Churn Salary](https://github.com/Curious-Creative-Mind/Banking-Customer-Churn-Analysis/blob/main/Churn%20Salary.png?raw=true)

### Credit Score

- The median Credit Score of both churned and not churned customers are almost same so Credit Score doesn't seems to impact customer churn.

![Churn Credit Score](https://github.com/Curious-Creative-Mind/Banking-Customer-Churn-Analysis/blob/main/Churn%20Credit_Score.png?raw=true)

### Credit Card

- Around 70% of customers have Credit Card but the churn rate seems to be similar for both customers having credit card and those without credit card.
- Thus having credit card doesn't affect customer churn.

![Churn Credit Card](https://github.com/Curious-Creative-Mind/Banking-Customer-Churn-Analysis/blob/main/Churn%20Credit_Card.png?raw=true)

### Number of Products

- Most of the customers have either 1 or 2 products while significantly low number of customers avail more than 2 products.
- Customers with more than 2 products are more likely to churn around 85%.
- Customers having 2 products are least likely to churn (0.07%) while 27% of customers with 1 product churned.

![Churn Products](https://github.com/Curious-Creative-Mind/Banking-Customer-Churn-Analysis/blob/main/Churn%20Products.png?raw=true)

### Tenure

- There seems to be no impact of Tenure on customer churn as churned customers are almost evenly distributed across Tenures.

![Churn Tenure](https://github.com/Curious-Creative-Mind/Banking-Customer-Churn-Analysis/blob/main/Churn%20Tenure.png?raw=true)

### Active Membership

- The number of Active customers are slightly more than inactive customers.
- Almost 26% within active membership category churned while 14% within inactive membership category churned.
- Almost 7% of churned customers were active members while almost twice (13%) of churned customers were inactive members.
- Thus inactive customers are more likely to churn.

![Churn Activeness](https://github.com/Curious-Creative-Mind/Banking-Customer-Churn-Analysis/blob/main/Churn%20Active_Mem.png?raw=true)

## Recommendations:

Based on the uncovered insights, the following recommendations have been provided :

- Banks from Germany should analyze banking facilities and services of branches in Spain and adopt similar strategies and customer experience to retain their customers as both countries have similar customer base.
- Special services tailored for female customers, targeted marketing campaigns along with focus on enhancing their overall customer experience can be developed to retain female customers.
- Special incentives and schemes targeting customers in the age group of 40-50 yrs such as house loans, car loans, education loans at low rates can be designed specifically catering to their needs. 
- Special offers, reward points and Loyalty programs for customers availing 2 banking products. Targeting and Convincing customers with 1 product to have 2 products.
- Engaging customers through regular communication and updates, launching Digital Banking Services along with assigning dedicated Customer Relationship Manager for each customer will help customers to remain active members.

### Data Source:

- Kaggle 

### Tools used:

- **Python-(Numpy, Pandas)** – for Data Cleaning, Data Transformation and EDA
- **Python-(Matplotlib, Seaborn)** – for Data Visualization and Data Analysis

### Skills applied and learned:

- Python (Numpy, Pandas, Matplotlib, Seaborn)
- Data Analysis and insights generation
- Data Storytelling
- Project Documentation

