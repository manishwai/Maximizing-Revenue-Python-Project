# **Maximizing Revenue with Yellow Taxi Data** ![Icon](https://img.icons8.com/ios-filled/50/000000/taxi.png)

## **Project Overview**

In the fast-paced taxi booking sector, maximizing revenue is crucial for long-term success and driver satisfaction. This project analyzes the Yellow Taxi dataset from NYC to explore the relationship between payment methods and fare amounts. Our goal is to leverage data-driven insights to enhance revenue streams for taxi drivers.

## **Problem Statement**

Our research aims to determine whether payment methods impact fare pricing and whether we can influence customers towards payment methods that generate higher revenue for drivers, without negatively affecting customer experience.

## **Research Questions**

1. Is there a relationship between total fare amount and payment type?
2. Can we nudge customers towards payment methods that generate higher revenue for drivers without negatively impacting their experience?

## **Data Overview**

The analysis utilizes the NYC Taxi Trip dataset, focusing on the following relevant columns:

- **passenger_count**: Number of passengers (1 to 5)
- **payment_type**: Payment method (card or cash)
- **fare_amount**: Fare amount in dollars
- **trip_distance**: Distance of the trip in miles
- **duration**: Duration of the trip in minutes

## **Methodology**

![image](https://github.com/user-attachments/assets/b2cb8ca3-7126-4b63-9a3d-513c93022f6a)

The methodology includes data cleaning, feature engineering, and statistical analysis to understand the impact of payment types on fare amounts.

## **Journey Insights**

- Customers paying with cards generally have a higher average trip distance and fare amount compared to cash payers. This suggests that card payments are associated with longer and more expensive trips.
  
  ![image](https://github.com/user-attachments/assets/4ac582c0-ab44-40a7-bcf0-d632334c2b05)
  ![image](https://github.com/user-attachments/assets/a7cf3948-bb99-4315-867d-a39ae03cb6cc)
  ![image](https://github.com/user-attachments/assets/4384b303-8ca6-44c7-bf36-9f95b076ed0b)

## **Payment Type Preferences**

- Card payments dominate, accounting for 67.5% of all transactions, compared to 32.5% for cash. This preference likely stems from convenience, security, or incentives for using cards.

  ![image](https://github.com/user-attachments/assets/09009a3b-5b69-47fd-97c4-d3a1a3ec1bdd)

## **Passenger Count Analysis**

- Single-passenger rides are predominant in both payment methods. For card payments, 40.08% are single-passenger rides, while cash payments have 20.04% for single-passenger rides. The percentage decreases with increasing passenger count, indicating that larger groups may prefer other transportation options or payment methods.

  ![image](https://github.com/user-attachments/assets/a619a79e-7fc1-466c-a310-964aec9a9c97)

## **Hypothesis Testing**

- **Null Hypothesis (H0)**: There is no difference in the average fare between customers using credit cards and those using cash.
- **Alternative Hypothesis (H1)**: There is a difference in the average fare between customers using credit cards and those using cash.

With a T-statistic of 165.5 and a P-value of less than 0.05, we reject the null hypothesis, indicating a significant difference in average fare between the two payment methods.

## **Recommendations**

1. **Encourage Card Payments**: Promote the use of credit cards to leverage the higher revenue potential associated with card transactions.
2. **Offer Incentives**: Implement strategies such as discounts or rewards for card payments to encourage customers to use this method.
3. **Enhance Payment Options**: Provide a seamless and secure credit card payment experience to increase customer adoption and convenience.

