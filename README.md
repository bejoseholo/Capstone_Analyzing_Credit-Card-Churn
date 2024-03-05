<h1 style="text-align: center; color: blue;"><u>Analyzing Customer Attrition in Our Bank's Credit Card Portfolio</u></h1>


## Context
Our bank has recently launched a range of premium credit card offerings, encompassing the Blue, Silver, Gold, and Platinum tiers. However, we have observed a notable uptick in customer attrition across these products in recent months. It is imperative for us to delve into the underlying factors driving this attrition, identify the customer segments most affected, and devise strategic measures to mitigate this trend effectively.

## Project Objective

1. **Analyze Customer Data:** Examine customer demographics and financial behavior to understand churn rates.

2. **Identify Churn Patterns:** Calculate churn rates and explore trends to pinpoint factors driving attrition.

3. **Evaluate Feature Importance:** Assess key factors contributing to customer churn for targeted intervention.

4. **Recommend Retention Strategies:** Provide actionable recommendations to improve customer retention based on data insights.

## Key Project Questions To be Answered

1. **Analyze Customer Data:**
   - What are the key demographic and financial attributes of customers in the dataset?
   - How do these attributes vary between attrited and existing customers?

2. **Identify Churn Patterns:**
   - What is the overall churn rate, and how has it changed over time?
   - Are there specific months or quarters with higher churn rates?
   - Are there demographic or financial patterns associated with higher churn rates?

3. **Evaluate Feature Importance:**
   - Which features (e.g., age, income, transaction history) are most influential in predicting customer churn?
   - How do these features contribute to the likelihood of attrition?

4. **Recommend Retention Strategies:**
   - Based on the analysis, what actionable strategies can be implemented to improve customer retention?
   - Are there specific interventions targeting identified churn factors?

## Dataset Description 

This analysis focuses on examining the data pertaining to customer attrition within our credit card portfolio fromn the last 12 months, known as "Bankchurners.csv" 

## Data Dictionary
`CLIENTNUM`: Client number. Unique identifier for the customer holding the account

`Attrition_Flag`: Internal event (customer activity) variable - if the account is closed then "Attrited Customer" else "Existing Customer"

`Customer_Age`: Age in Years

`Gender`: Gender of the account holder

`Dependent_count`: Number of dependents.

`Education_Level`:  Educational Qualification of the account holder - Graduate, High School, Unknown, Uneducated, College(refers to a college student), Post-Graduate, Doctorate.

`Marital_Status`: Marital Status of the account holder.

`Income_Category`: Annual Income Category of the account holder (USD).

`Card_Category`: Type of Card.

`Months_on_book`: Period of relationship with the bank (months).

`Total_Relationship_Count`: Total no. of products held by the customer.

`Months_Inactive_12_mon`: No. of months inactive in the last 12 months.

`Contacts_Count_12_mon`: No. of Contacts between the customer and bank in the last 12 months.

`Credit_Limit`: Credit Limit on the Credit Card (USD).

`Total_Revolving_Bal`: The balance that carries over from one month to the next is the revolving balance (USD).

`Avg_Open_To_Buy`: Open to Buy refers to the amount left on the credit card to use (Average of last 12 months) (USD).

`Total_Trans_Amt`: Total Transaction Amount (Last 12 months) (USD).

`Total_Trans_Ct`: Total Transaction Count (Last 12 months).

`Total_Ct_Chng_Q4_Q1`: Ratio of the total transaction count in 4th quarter and the total transaction count in 1st quarter.

`Total_Amt_Chng_Q4_Q1`: Ratio of the total transaction amount in 4th quarter and the total transaction amount in 1st quarter.

`Avg_Utilization_Ratio`: Represents how much of the available credit the customer spent.
