![image](https://github.com/user-attachments/assets/205df250-ad93-41c1-8b5e-fa1efb0d7cff)![image](https://github.com/user-attachments/assets/bd1ee4a4-1730-4b9d-9237-9138cfcb5b58)![image](https://github.com/user-attachments/assets/645ace87-ae3f-4f4f-ab27-07e7a78f3087)![image](https://github.com/user-attachments/assets/a39482e5-766a-4c6d-a1f2-1fd9ae835035)# FlyingWhale Airline Case Study

## Table of Contents

1. [Executive Summary](#executive-summary)
2. [Introduction](#introduction)
3. [Data Overview](#data-overview)
   - 3.1 [Customer Flight Activity](#customer-flight-activity)
   - 3.2 [Customer Loyalty History](#customer-loyalty-history)
4. [Flight Activity Analysis](#flight-activity-analysis)
   - 4.1 [Monthly and Yearly Flight Booking Patterns](#monthly-and-yearly-flight-booking-patterns)
   - 4.2 [Correlation Between Flight Distance and Loyalty Points Accumulated](#correlation-between-flight-distance-and-loyalty-points-accumulated)
   - 4.3 [Impact of Companion Bookings on Loyalty Points Redeemed](#impact-of-companion-bookings-on-loyalty-points-redeemed)
5. [Loyalty Segmentation](#loyalty-segmentation)
   - 5.1 [Customer Segmentation by Loyalty Card Status](#customer-segmentation-by-loyalty-card-status)
   - 5.2 [Demographics and Customer Behaviors](#demographics-and-customer-behaviors)
   - 5.3 [Customer Lifetime Value (CLV) Across Loyalty Segments](#customer-lifetime-value-clv-across-loyalty-segments)
6. [Enrollment and Cancellation Trends](#enrollment-and-cancellation-trends)
   - 6.1 [Average Enrollment Duration Among Cancelled Members by Province](#average-enrollment-duration-among-cancelled-members-by-province)
   - 6.2 [Popular Months for Cancellations](#popular-months-for-cancellations)
   - 6.3 [Cancellations by Education and Marital Status](#cancellations-by-education-and-marital-status)
   - 6.4 [Loyalty Card Members with Lowest Enrollment Duration](#loyalty-card-members-with-lowest-enrollment-duration)
7. [Recommendations](#recommendations)

## Executive Summary

This report presents a comprehensive analysis of FlyingWhale Airline's customer flight activity and loyalty program performance. The analysis focuses on flight booking patterns, loyalty segmentation, and enrollment and cancellation trends. Key findings include:

- **Flight Activity Analysis:**
  - July is the peak month for flight bookings, particularly in 2017 and 2018.
  - A strong positive correlation exists between flight distance and loyalty points accumulated.
  - Members traveling with companions redeem significantly more loyalty points, especially in groups of 10.

    ![image](https://github.com/user-attachments/assets/9a470b1c-565b-4012-84d6-1ba825440dbf)


- **Loyalty Segmentation:**
  - The Star loyalty card tier has the highest number of flights booked.
  - Males book slightly more flights than females, particularly with the Star loyalty card.
  - Married individuals and bachelor students constitute the largest segments of loyalty members.

    ![image](https://github.com/user-attachments/assets/6a2ec337-858f-49b7-91d9-ed7a17a6ff8b)


- **Enrollment and Cancellation Trends:**
  - Cancellations have increased exponentially, peaking in December, August, and November.
  - New Brunswick members have the longest average enrollment duration.
  - Married and bachelor students exhibit the highest cancellation rates.


    ![image](https://github.com/user-attachments/assets/7694c430-3715-4342-935e-dea0f3096428)


**Recommendations:** Focus on enhancing customer retention, optimizing the loyalty program, and targeting specific customer segments to improve overall performance.

## Introduction

FlyingWhale Airline aims to enhance its business intelligence capabilities by analyzing customer flight activity and loyalty history. This report provides insights into customer behaviors, loyalty program effectiveness, and areas for improvement to optimize customer experience and retention.

## Data Overview

Two primary datasets were analyzed:

### Customer Flight Activity:
- **Key Fields:** Loyalty Number, Year and Month, Flights Booked, Flights with Companions, Total Flights, Distance, Points Accumulated, Points Redeemed, Dollar Cost Points Redeemed.

### Customer Loyalty History:
- **Key Fields:** Loyalty Number, Demographics (Country, Province, City, Postal Code, Gender, Education, Salary, Marital Status), Loyalty Card, Customer Lifetime Value (CLV), Enrollment Details, Cancellation Details.

## Flight Activity Analysis

### Monthly and Yearly Flight Booking Patterns

#### Findings:
- **Peak Booking Months:** July 2017 and July 2018 had the highest number of bookings.
  - Total Flights in July: 246,298 flights.
  - By Loyalty Card:
    - Star: 112,219 flights.
    - Nova: 81,772 flights.
    - Aurora: 51,307 flights.

#### Analysis:
- **Seasonal Trends:** The data indicates a significant increase in bookings during July, suggesting peak travel season.
- **Loyalty Card Performance:** The Star loyalty card members are the most active during peak months.

#### Visualization:
Line chart depicting monthly bookings, sorted chronologically to ensure proper month sequencing, with year as the label.

![image](https://github.com/user-attachments/assets/810f5734-57ee-474c-8e47-529f0da79aee)


### Correlation Between Flight Distance and Loyalty Points Accumulated

#### Findings:
- There is a strong positive correlation between average distance traveled and loyalty points accumulated.
- Longer flights result in higher points accumulation.

#### Analysis:
- **Incentivization Effectiveness:** The loyalty program effectively incentivizes customers to book longer flights.
- **Customer Engagement:** Customers are likely aware of the benefits associated with longer flights, increasing engagement with the loyalty program.

#### Visualization:
Scatter plot with a trend line demonstrating the positive correlation between distance and points accumulated.

![image](https://github.com/user-attachments/assets/4070d8aa-c4cc-4ee4-81a2-e02e2a82a4e2)


### Impact of Companion Bookings on Loyalty Points Redeemed

#### Findings:
- **Highest Points Redeemed:** Groups of 10 companions had the highest average points redeemed at 139.73 points.
- **Comparison to Solo Travelers:** This is 20,750.28 times higher than the average points redeemed by individuals traveling alone (0.67 points).
- **Range of Points Redeemed:** Across all companion bookings, average points redeemed ranged from 0.67 to 139.73.

#### Analysis:
- **Group Travel Benefits:** The loyalty program significantly benefits group travelers, encouraging customers to book with companions.
- **Redemption Patterns:** Higher points redemption in larger groups suggests customers utilize points more when traveling with others.

#### Visualization:
Bar charts showing points redeemed across different numbers of companions.

![image](https://github.com/user-attachments/assets/0b6d497c-bfca-4566-bebd-0fc094f29cb8)


## Loyalty Segmentation

### Customer Segmentation by Loyalty Card Status

#### Findings:
- **Total Flights by Loyalty Card:**
  - Star: Highest number of flights booked.
  - Nova: Second highest.
  - Aurora: Lowest among the three.

#### Analysis:
- **Loyalty Tier Engagement:** Customers with Star loyalty cards are more engaged, indicating higher satisfaction or better perks associated with this tier.
- **Marketing Focus:** Potential to target Nova and Aurora members with incentives to increase their flight bookings.

#### Visualization:
Line charts displaying total flights by loyalty card across months.

![image](https://github.com/user-attachments/assets/33dadbfd-88e3-47af-b50d-e5e8018135d0)


### Demographics and Customer Behaviors

#### Gender Analysis:
- **Total Flights Booked:**
  - Males: 836,166 flights.
  - Females: 832,998 flights.
- **Average Flights Booked:**
  - Males: 278,722 flights.
  - Females: 277,666 flights.
- **Largest Disparity:** With the Star loyalty card, males booked 8,098 more flights than females.

#### Marital Status:
- **Largest Segments:**
  - Married individuals and bachelor students constitute the largest number of loyalty members.

#### Analysis:
- **Gender Trends:** Males are slightly more active in flight bookings, especially in higher loyalty tiers.
- **Marital Status Influence:** Married individuals and bachelor students are significant customer segments, potentially due to travel needs related to family or education.

#### Visualization:
- Pie chart showing flights booked by loyalty card and gender.
- Pie chart depicting loyalty members by marital status.

  ![image](https://github.com/user-attachments/assets/8cde55e8-5421-4efe-86c4-48371ea88297)


### Customer Lifetime Value (CLV) Across Loyalty Segments

#### Findings:
- **Highest Average CLV:** The Star loyalty card tier has customers with the highest average CLV.
- **CLV Trends:** There is a direct correlation between loyalty tier and CLV, with higher tiers contributing more to revenue.

#### Analysis:
- **Revenue Contribution:** Customers in higher loyalty tiers are more valuable over their lifetime.
- **Loyalty Program Impact:** The loyalty program effectively retains high-value customers.

#### Visualization:
Pie charts showing CLV trends across loyalty segments.

![image](https://github.com/user-attachments/assets/f7320dd1-d182-4283-9003-953d541ee434)


## Enrollment and Cancellation Trends

### Average Enrollment Duration Among Cancelled Members by Province

#### Findings:
- **Longest Enrollment Duration:** New Brunswick has the longest average enrollment duration among cancelled members at 19.20 months.
- **Fastest Cancellations:** [Insert Province] sees members cancelling the fastest (specific data needed).

#### Analysis:
- **Regional Retention:** Certain provinces have better retention rates, possibly due to regional preferences or effective local marketing.
- **Opportunity Areas:** Provinces with faster cancellations present opportunities for targeted retention strategies.

#### Visualization:
Map visualization highlighting average enrollment duration by province.

![image](https://github.com/user-attachments/assets/cd000934-62a3-4527-b322-3e28b97a6005)


### Popular Months for Cancellations

#### Findings:
- **Peak Cancellation Months:** December, August, and November have the highest number of cancellations.
- **Trend:** Cancellations have increased exponentially each year.

#### Analysis:
- **Seasonal Factors:** High cancellations during these months may be due to seasonal travel changes or customer dissatisfaction.
- **Predictive Insights:** Understanding these patterns can help in developing strategies to reduce cancellations during peak times.

#### Visualization:
Column charts displaying cancellations by month over several years.

![image](https://github.com/user-attachments/assets/821829b2-cb83-49a2-aff4-001bd74c2dd8)


### Cancellations by Education and Marital Status

#### Findings:
- **Highest Cancellations:**
  - Married individuals and bachelor students had the most cancellations, each with 865 cancellations.
- **Demographics at Risk:** These groups are more likely to cancel their memberships.

#### Analysis:
- **Customer Needs:** Married individuals and bachelor students may have changing travel needs or face budget constraints.
- **Retention Efforts:** Tailored strategies could address specific concerns of these demographics.

#### Visualization:
Clustered bar charts showing cancellations by education level and marital status.

![image](https://github.com/user-attachments/assets/445194c3-d0b9-4626-9183-fc489c630afb)


### Loyalty Card Members with Lowest Enrollment Duration

#### Findings:
- **Lowest Enrollment Duration:** [Insert Loyalty Card Tier] members have the lowest enrollment duration among cancellations.
- **Churn Risk:** Members in this tier are more prone to early cancellation.

#### Analysis:
- **Program Evaluation:** The benefits offered at this loyalty tier may not meet customer expectations.
- **Improvement Areas:** Enhancing the value proposition could improve retention.

#### Visualization:
Bar charts showing minimum enrollment duration by loyalty card tier.

![image](https://github.com/user-attachments/assets/47a1ab1c-a2a5-4076-8527-8105ddf32f6e)


## Recommendations

Based on the analysis, the following strategies are recommended:

### Enhance Loyalty Program Benefits:
- **For Lower Tiers:** Improve perks for Nova and Aurora members to increase engagement and retention.
- **For High-Risk Demographics:** Offer customized incentives for married individuals and bachelor students.

### Targeted Marketing Campaigns:
- **Gender-Specific Promotions:** Develop campaigns aimed at increasing female engagement, especially with the Star loyalty card.
- **Group Travel Offers:** Capitalize on the high points redemption among companion travelers by promoting group discounts.

### Address Seasonal Cancellations:
- **Retention Initiatives:** Implement retention programs before peak cancellation months (December, August, November).
- **Feedback Mechanisms:** Collect customer feedback to understand reasons for cancellations during these periods.

### Regional Strategies:
- **Province-Specific Programs:** Focus on provinces with faster cancellation rates, tailoring strategies to local customer preferences.
- **Leverage Strong Regions:** Use successful tactics from regions like...
