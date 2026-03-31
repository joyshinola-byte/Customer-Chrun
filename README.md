Introduction

Customer churn analysis helps businesses understand why customers leave their services.
This project uses synthetic data to analyze customer behavior and identify churn patterns.

 Problem Statement

Customer churn leads to revenue loss and increased customer acquisition cost.
Manual analysis of large customer data is time-consuming and inefficient.

Objective

The objective of this project is to perform Exploratory Data Analysis (EDA) on customer data.
It aims to identify patterns, trends, and key factors influencing customer churn.

 Dataset Overview

This project uses a synthetically generated dataset of 1,00,000 customers.
The dataset simulates real-world banking or telecom customer data.

 Dataset Features (Columns Used)
 
Customer_ID – Unique ID for each customer

Age – Customer age (18–70)

Gender – Male / Female

Tenure – Years with company (0–10)

Balance – Account balance

CreditScore – Credit score (300–900)

EstimatedSalary – Annual income

NumOfProducts – Number of products used

IsActiveMember – Active status (Yes/No)

Churn – Target variable (0 = No, 1 = Yes)

Tools & Technologies

Python
Google Colab
Pandas
NumPy
Matplotlib
Seaborn
Faker (for data generation)

Methodology

1. Data Generation

Synthetic customer data is generated using Faker and NumPy.
It simulates real-world customer attributes and behavior.

2. Data Preprocessing

Missing values are checked and data types are verified.
Categorical data is converted into numerical format.

3. Exploratory Data Analysis (EDA)

Statistical measures like mean, median, and standard deviation are calculated.
Data is analyzed to understand distribution and trends.

4. Churn Analysis

Customers are divided into churn and non-churn groups.
Patterns and differences between these groups are studied.

5. Group-Based Analysis

Churn is analyzed based on age, gender, activity, and product usage.
This helps identify high-risk customer segments.

6. Relationship Analysis

Relationships between variables like balance, salary, and credit score are analyzed.
Correlation is used to understand feature impact on churn.

7. Data Visualization

Various charts are used:

Bar charts
Pie charts
Histograms
Scatter plots
Box plots
Heatmaps

 Key Insights

Inactive customers are more likely to churn.
Customers with low balance tend to leave more frequently.
Product usage and tenure also influence churn behavior.

 Conclusion

Customer churn can be reduced by identifying key patterns and behaviors.
Businesses can take preventive actions based on data insights to retain customers.

                                                        OUTPUT



<img width="685" height="467" alt="Screenshot 2026-03-31 162228" src="https://github.com/user-attachments/assets/064a3afe-ebb6-45ae-94b5-8f5d283e7515" />



<img width="417" height="417" alt="Screenshot 2026-03-31 162239" src="https://github.com/user-attachments/assets/fa31d0de-4524-4bd0-8cf3-86ccc750e043" />


<img width="637" height="456" alt="Screenshot 2026-03-31 162251" src="https://github.com/user-attachments/assets/bbecf1a0-e39b-4c97-a40d-439116259efc" />


<img width="676" height="469" alt="Screenshot 2026-03-31 162259" src="https://github.com/user-attachments/assets/648b30ec-cbae-4e3f-97e8-6728b28ce117" />


<img width="640" height="468" alt="Screenshot 2026-03-31 162307" src="https://github.com/user-attachments/assets/96557048-af9a-472d-b541-c164cd567656" />


<img width="787" height="653" alt="Screenshot 2026-03-31 162321" src="https://github.com/user-attachments/assets/917d90d5-0ca6-4c76-a7ce-5b5f3d45838e" />



                                                
