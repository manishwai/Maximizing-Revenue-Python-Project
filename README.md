# Maximizing-Revenue-Python-Project
Analyzing the Yellow Taxi Data Set Available on Kaggle and Analyze the Relation Between Payment Type and fare amount and other analysis 

Problem Statment 
In the fast-paced taxi booking sector, making the most of revenue is essential for long-term success and driver happiness.
Our goal is to use data-driven insights to maximize revenue streams for taxi drivers in order to meet this need. Our research aims to determine whether payment methods have an impact on fare pricing by focusing on the relationship between payment type and fare amount..

Resarch Questions 
Is there a relationship between total fare amount and payment type?
Can we nudge customers towards payment methods that generate higher revenue for drivers, without negatively impacting customer experience?

Data Overview 
For this analysis, we utilized the comprehensive dataset off NYC Taxi Trip records, used data cleaning and feature engineering procedures to concentrate solely on the relevant columns essential for our investigation

Relevant columns used for this research
tpassenger_count (1 to 5)
payment_type (card or cash)
fare_amounttrip_distance (miles)
duration (minutes)

Methodology 
![image](https://github.com/user-attachments/assets/b2cb8ca3-7126-4b63-9a3d-513c93022f6a)

Journey Insights 
Customers paying with cards tend to have a slightly higher average trip distance and fare amount compared to those paying with cash.
Indicates that customers prefers to pay more with cards when they have high fare amount and long trip distance.
![image](https://github.com/user-attachments/assets/4ac582c0-ab44-40a7-bcf0-d632334c2b05)
![image](https://github.com/user-attachments/assets/a7cf3948-bb99-4315-867d-a39ae03cb6cc)
![image](https://github.com/user-attachments/assets/4384b303-8ca6-44c7-bf36-9f95b076ed0b)

Payment Type Preferences
![image](https://github.com/user-attachments/assets/09009a3b-5b69-47fd-97c4-d3a1a3ec1bdd)
The proportion of customers paying with cards is significantly higher than those paying with cash, with card payments accounting for 67.5% of all transactions compared to cash payments at32.5%.
This indicates a strong preference among customers for using card payments over cash, potentially due to convenience, security, or incentives offered for card transactions.

Passenger Count Analysis
![image](https://github.com/user-attachments/assets/a619a79e-7fc1-466c-a310-964aec9a9c97)
Among card payments, rides with a single passenger (passenger count = 1) comprise the largest proportion , constituting 40.08% of all card transactions.
Similarly, cash payments are predominantly associated with single-passenger rides, making up 20.04% of all cash transactions .
There is a noticeable decrease in the percentage of transactions as the passenger count increases, suggesting that larger groups are less likely to use taxis or may opt for alternatives payment methods .
These insights emphasize the importance of considering both payment method and passenger count when analyzing transaction data, as they provide valuable insights into customer behavior and preferences

Hypothesis Testing
Null hypothesis: There is no difference in average fare between customers who use credit cards and customers who use cash.
Alternative hypothesis: There is a difference in average fare between customers who use credit cards and customers who use cash With a T-statistic of 165.5 and a P-value of less than 0.05, 
We reject the null hypothesis, suggesting that there is indeed a significant difference in average fare between the two payment methods.



Recommendations 
Encourage customers to pay with credit cards to capitalize on the potential for generating more revenue for taxi cab drivers.
Implement strategies such as offering incentives or discounts for credit card transactions to incentivize customers to choose this payment method.
Provide seamless and secure credit card payment options to enhance customer convenience and encourage adoption of this preferred payment method.
