# Customer Churn Analysis In The Telecommunication Industry
___
![](https://github.com/Judithkyerewaa/Telecommunication-Customer-Churn-Analysis/blob/main/customer_churn.png)
***
## Introduction

This Power BI project investigates customer churn in the telecommunications industry, aiming to uncover key drivers of customer attrition and provide actionable insights for improving customer retention. By analyzing customer demographics, service preferences, and behavior patterns, this project equips stakeholders with data-driven strategies to reduce churn, enhance customer satisfaction, and boost revenue.

**Key decision-makers** such as customer support managers, product development teams, IT operations and marketing strategists can use these insights to refine service offerings, improve engagement and foster long-term customer loyalty.

## Problem Statement

Customer churn is a critical challenge for telecommunication companies, leading to revenue loss, increased costs for customer acquisition, and reduced loyalty. Customers often leave due to unmet expectations, dissatisfaction with services, or better offers from competitors.

**Key Drivers of Churn Include:** 
1. Poor service quality and limited engagement.
2. High costs associated with certain services or payment methods.
3. Lack of personalization or targeted retention efforts for high-risk groups.

This project focuses on identifying and addressing the root causes of churn, to strengthen retention strategies and improve customer satisfaction.

## Project Objectives

1. Analyze Customer Demographics: Understand how factors like age, partnership status, and dependents influence churn.
2. Evaluate Tenure Dynamics: Examine churn trends during the critical first year and beyond to identify key retention opportunities.
3. Assess Contract Types and Payment Methods: Investigate how contract duration and payment options affect churn rates.
4. Promote Essential Services: Determine the role of additional services like Online Security and Tech Support in reducing churn.
5. Optimize Pricing Strategies: Explore churn rates across pricing tiers to refine offerings for better value and customer satisfaction.

## Data Overview
**Dataset:** The analysis uses a publicly available telecom churn dataset. [Click Here](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

**Structure:**
21 columns capturing customer demographics, service preferences, payment details, and churn status.
Each row represents a unique customer.

Industry Focus: Telecommunications.


## Tools Used:
- Data Cleaning: Power BI (Power Query).
- Analysis and Visualization: Power BI dashboards and DAX formulas for custom measures.
- Other power BI features that were incorporated include filters and data modelling.

 


## Data Transformations:
- Converted binary columns (e.g., Senior Citizen) into more readable formats (Yes/No).
- Grouped numerical columns (e.g., Tenure, Monthly Charges) for better visualization.
- Created calculated measures such as total churned customers, total cutomers and churn rate by segment to enhance insights.




 ## Data Modelling
  The data model began with a flat file containing customer churn data and was enhanced by adding a services table, detailing the services used by customers, and a reference table. Both tables are directly connected to the customer churn data, enabling deeper insights and a more comprehensive analysis.

  ![](https://github.com/Judithkyerewaa/Telecommunication-Customer-Churn-Analysis/blob/main/data_model.PNG)


***

## Executive Summary

### Overview And Findings


![](https://github.com/Judithkyerewaa/Telecommunication-Customer-Churn-Analysis/blob/main/dashboard.PNG)    
***
![](https://github.com/Judithkyerewaa/Telecommunication-Customer-Churn-Analysis/blob/main/dashboard_2.PNG)


- Overall Churn Rate: 26.5% (1,869 of 7,043 customers).
  **Highest Risk Groups:**
-  New Customers (0–12 Months): 47.4% churn rate.
-  Month-to-Month Contracts type: 42.7% churn rate.
-  Senior Citizens: 41.7% churn rate.
-  Electronic Check Payment Users: 45.3% churn rate.
-  Customers without Online Security: 78.17% churn rate.

Addressing these challenges with tailored onboarding programs, enhanced service offerings, improved payment systems, and senior-specific support can significantly boost retention, reducing churn and safeguarding revenue.  

**Financial Impact:**
- Total monthly revenue of all customers: **$456,120.**
- Reducing churn by **10%** would recover **$12,115.86/month** or **$145,390.32/year**.
***


## Insights Deep Dive



## Customer Demographics

### Customer Churn by Senior Citizen (Age)


![](https://github.com/Judithkyerewaa/Telecommunication-Customer-Churn-Analysis/blob/main/churn_by_senior_citizen.PNG)


 The analysis shows that senior citizens (aged 65 and above) have a much higher churn rate compared to non-senior customers. Of 1,142 senior citizens, 476 churned, giving a churn rate of 41.7%, which is much higher than the 23.6% (1,393 churned customers) churn rate for non-senior customers.

**Insight:** Offer age-specific discounts, easy-to-use tech support hotlines, and workshops for navigating services.

### Customer Churn by Partner Status and dependents
Customers without partners are more likely to churn with 33.0% (1,200 churned customers) churn rate compared to those with partners 19.7% (669) churn rate.   Customers without dependents are more likely to churn (31.3%)churn rate (1,543 churned customers) compared to those with dependents (15.5%) (326).

**Insight:** Craft marketing strategies to appeal to single customers by emphasizing flexibility, personalization, or added value.

___


## Customer Account Information

### Customer Churn by Tenure


![](https://github.com/Judithkyerewaa/Telecommunication-Customer-Churn-Analysis/blob/main/churn_by_tenure.PNG)


New customers (0–12 months) are the most likely to churn, with 1,037 customers churning . Chart show a steep decline in churn after 12 months of tenure, underlining the importance of retaining customers in their first year.

**Insight:** Strengthen onboarding experiences with proactive communication, tailored offers, and quick resolution of early-stage complaints.







### Customer Churn by Payment Methods


![](https://github.com/Judithkyerewaa/Telecommunication-Customer-Churn-Analysis/blob/main/churn_by_payment_method.PNG)


Customers using electronic checks have the highest churn rate of 45.3% with 1,071 customers churning as compared to other payment methods such as mailed checks, bank transfers (automatic), and credit card (automatic) payments.
**Insight:** Introduce user-friendly online payment platforms and incentives for setting up automatic payments. 







### Customer Churn by Contract Types


![](https://github.com/Judithkyerewaa/Telecommunication-Customer-Churn-Analysis/blob/main/churn_by_contract_type.PNG)


Customers on the Month-to-month contract type have the highest churn rate of 42.7% (1,655 churned customers), whereas one-year has 11.3% churn rate(166 churned customers) and two-year 2.8% churn rate (48 churned customers) which exhibit significantly lower churn.This indicates that shorter contracts, such as month-to-month agreements, are more prone to churn, likely due to the ease of contract termination. 

**Insight:** Offer loyalty programs, discounts, or perks to encourage longer-term contracts, particularly for customers nearing the end of their month-to-month agreements.


___





## Internet and Account Services


### Churn by Internet Services

![](https://github.com/Judithkyerewaa/Telecommunication-Customer-Churn-Analysis/blob/main/churn_by_internet_service.PNG)


Fiber optic users show a high churn rate of 41.9% (1,297 churned customers), likely due to perceived high costs or dissatisfaction with service quality. DSL customers have a much lower churn, with only 459 customers churning. Those without internet service have the lowest churn, with just 113 churned customers, likely because they depend less on telecom services. 

**Insight:** Investigating cost or quality concerns for fiber optic customers can address high churn.

___



## Services


### Churn by Customer Account Services


![](https://github.com/Judithkyerewaa/Telecommunication-Customer-Churn-Analysis/blob/main/churn_by_account_services.PNG)



Customers without Online Security (78.17% churn rate) or Tech Support (77.37% churn rate) are most likely to churn. Paperless Billing users also experience a high churn rate of (74.91%).

Insight: Promote the adoption of these essential services by highlighting their value in preventing disruptions or resolving issues quickly.   

___



## Financial Metrics

### Customer Churn by Monthly Charges


![](https://github.com/Judithkyerewaa/Telecommunication-Customer-Churn-Analysis/blob/main/churn_by_monthly_charges.PNG)


Customers paying between $50–100 per month have the highest churn rate of 33.5% (1,251 churned customers), compared to lower churn rates for those paying under $20 with 5.5% churn rate (55 churned customers) or over $100 with 15.2% (257 churned customers).

**Insight:** Reassess the mid-tier pricing strategy by adding more features, offering discounts, or improving service quality for this segment.



___


## Recommendations



**1. Better Onboarding for New Customers (0–12 Months)**
   
- What to Do: Improve the onboarding process for new customers, as they have the highest churn rate (47.4%). This includes clear communication, personalized offers, and quick problem resolution during the first few months. Examples include exclusive deals for new customers or regular check-ins to ensure they are satisfied.

- Why It Matters: The first year is crucial for building trust and loyalty. Keeping customers engaged early increases their chances of staying longer, leading to higher profits.



**2. Encourage Long-Term Contracts**
   
- What to Do: Customers on month-to-month plans (42.7% churn rate) are more likely to churn. Offer discounts, loyalty rewards, or perks to encourage them to sign one- or two-year contracts. Also, remind customers nearing the end of their contracts to renew.

- Why It Matters: Long-term contracts reduce the chance of customers leaving and ensure steady revenue.



**3. Simplify Payments for Electronic Check Users**
   
- What to Do: Customers using electronic checks have the highest churn rate (45.3%). Offer easier online payment options and incentives for setting up automatic payments.

- Why It Matters: Simplifying payments makes it easier for customers to stay, improving satisfaction and reducing churn.



**4. Support for Senior Citizens**
   
- What to Do: Senior citizens (41.7% churn rate) need tailored support like simple service plans, easy-to-use tech help, and workshops to guide them.

- Why It Matters: Special care for seniors builds loyalty and helps reduce churn. Engaging this group ensures they stay longer, boosting revenue.



**5. Promote Key Services (Online Security, Tech Support)**

- What to Do: Customers without Online Security (78.17% churn rate) or Tech Support (77.37% churn rate) are more likely to churn. Educate them on the benefits of these services and make them easy to access.

- Why It Matters: These services are important to customers. Promoting them reduces churn and improves overall satisfaction.



**6. Improve Mid-Tier Pricing Plans ($50–100)**

- What to Do: Customers paying $50–100 per month (33.5% churn rate) are most likely to leave. Add more features, give discounts, or improve service quality to make these plans more attractive.

- Why It Matters: Better mid-tier plans provide more value, helping retain customers who might feel the pricing doesn’t match the service.



**7.  Personalized Marketing for Specific Groups**
   
- What to Do: Use targeted promotions to reach groups like single customers (33.0% churn rate) or those with dependents (15.5% churn rate). Highlight flexibility, discounts, or added benefits tailored to their needs.

- Why It Matters: Personalization meets customer needs, building loyalty and reducing churn.



___





## Assumptions and Caveats
### Assumptions
- The dataset is accurate, complete, and free of errors such as duplicates or incorrect entries.
- All columns and data values correctly represent real-world customer attributes and their interactions with the telecom company.
- Key terms like “churn” and “tenure” are defined consistently throughout the dataset, with no confusion about their meaning or measurement.


### Caveats (Limitations)
- The dataset does not account for external factors, such as promotions from competitors, economic conditions, or policy changes, which might also influence customer churn.
- It does not include customer feedback or satisfaction data, which could provide deeper insights into the reasons for churn.
- The definition of “churn” might oversimplify situations, such as customers who temporarily disconnect services or later reactivate their accounts.
- Calculation for revenue recovery assumes that all customers retained through churn reduction efforts will continue paying their current monthly charges, without considering potential changes like service upgrades or downgrades.
























