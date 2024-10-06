# FlyingWhale-Airline-Case-Study
# Contents
1. [Executive Summary](#executive-summary)	3
2. [Introduction](#introduction)	3
3. [Data Overview](#data-overview)	3
   1. [Customer Flight Activity](#customer-flight-activity)	3
   2. [Customer Loyalty History](#customer-loyalty-history)	4
4. [Flight Activity Analysis](#flight-activity-analysis)	4
   1. [Monthly and Yearly Flight Booking Patterns](#monthly-and-yearly-flight-booking-patterns)	4
      1. [Findings](#findings-1)	4
      2. [Analysis](#analysis-1)	4
      3. [Visualization](#visualization-1)	4
   2. [Correlation Between Flight Distance and Loyalty Points Accumulated](#correlation-between-flight-distance-and-loyalty-points-accumulated)	4
      1. [Findings](#findings-2)	4
      2. [Analysis](#analysis-2)	4
      3. [Visualization](#visualization-2)	5
   3. [Impact of Companion Bookings on Loyalty Points Redeemed](#impact-of-companion-bookings-on-loyalty-points-redeemed)	5
      1. [Findings](#findings-3)	5
      2. [Analysis](#analysis-3)	5
      3. [Visualization](#visualization-3)	5
5. [Loyalty Segmentation](#loyalty-segmentation)	5
   1. [Customer Segmentation by Loyalty Card Status](#customer-segmentation-by-loyalty-card-status)	5
      1. [Findings](#findings-4)	5
      2. [Analysis](#analysis-4)	5
      3. [Visualization](#visualization-4)	5
   2. [Demographics and Customer Behaviors](#demographics-and-customer-behaviors)	6
      1. [Gender Analysis](#gender-analysis)	6
      2. [Marital Status](#marital-status)	6
      3. [Analysis](#analysis-5)	6
      4. [Visualization](#visualization-5)	6
   3. [Customer Lifetime Value (CLV) Across Loyalty Segments](#customer-lifetime-value-clv-across-loyalty-segments)	6
      1. [Findings](#findings-5)	6
      2. [Analysis](#analysis-6)	6
      3. [Visualization](#visualization-6)	6
6. [Enrollment and Cancellation Trends](#enrollment-and-cancellation-trends)	7
   1. [Average Enrollment Duration Among Cancelled Members by Province](#average-enrollment-duration-among-cancelled-members-by-province)	7
      1. [Findings](#findings-6)	7
      2. [Analysis](#analysis-7)	7
      3. [Visualization](#visualization-7)	7
   2. [Popular Months for Cancellations](#popular-months-for-cancellations)	7
      1. [Findings](#findings-7)	7
      2. [Analysis](#analysis-8)	7
      3. [Visualization](#visualization-8)	7
   3. [Cancellations by Education and Marital Status](#cancellations-by-education-and-marital-status)	7
      1. [Findings](#findings-8)	7
      2. [Analysis](#analysis-9)	8
      3. [Visualization](#visualization-9)	8
   4. [Loyalty Card Members with Lowest Enrollment Duration](#loyalty-card-members-with-lowest-enrollment-duration)	8
      1. [Findings](#findings-9)	8
      2. [Analysis](#analysis-10)	8
      3. [Visualization](#visualization-10)	8
7. [Recommendations](#recommendations)	8
   1. [Enhance Loyalty Program Benefits](#enhance-loyalty-program-benefits)	8
   2. [Targeted Marketing Campaigns](#targeted-marketing-campaigns)	8
   3. [Address Seasonal Cancellations](#address-seasonal-cancellations)	8
   4. [Regional Strategies](#regional-strategies)	9
   5. [Enhance Customer Experience](#enhance-customer-experience)	9
8. [Conclusion](#conclusion)	9

## 1. Executive Summary
This report presents a comprehensive analysis of FlyingWhale Airline's customer flight activity and loyalty program performance. The analysis focuses on flight booking patterns, loyalty segmentation, and enrollment and cancellation trends. Key findings include:

- **Flight Activity Analysis:**
  - July is the peak month for flight bookings, particularly in 2017 and 2018.
  - A strong positive correlation exists between flight distance and loyalty points accumulated.
  - Members traveling with companions redeem significantly more loyalty points, especially in groups of 10.
  
- **Loyalty Segmentation:**
  - The Star loyalty card tier has the highest number of flights booked.
  - Males book slightly more flights than females, particularly with the Star loyalty card.
  - Married individuals and bachelor students constitute the largest segments of loyalty members.
  
- **Enrollment and Cancellation Trends:**
  - Cancellations have increased exponentially, peaking in December, August, and November.
  - New Brunswick members have the longest average enrollment duration.
  - Married and bachelor students exhibit the highest cancellation rates.

**Recommendations:** Focus on enhancing customer retention, optimizing the loyalty program, and targeting specific customer segments to improve overall performance.

## 2. Introduction
FlyingWhale Airline aims to enhance its business intelligence capabilities by analyzing customer flight activity and loyalty history. This report provides insights into customer behaviors, loyalty program effectiveness, and areas for improvement to optimize customer experience and retention.

## 3. Data Overview
Two primary datasets were analyzed:

### 3.1 Customer Flight Activity:
- **Key Fields:** Loyalty Number, Year and Month, Flights Booked, Flights with Companions, Total Flights, Distance, Points Accumulated, Points Redeemed, Dollar Cost Points Redeemed.

### 3.2 Customer Loyalty History:
- **Key Fields:** Loyalty Number, Demographics (Country, Province, City, Postal Code, Gender, Education, Salary, Marital Status), Loyalty Card, Customer Lifetime Value (CLV), Enrollment Details, Cancellation Details.

## 4. Flight Activity Analysis
### 4.1 Monthly and Yearly Flight Booking Patterns
#### 4.1.1 Findings:
- **Peak Booking Months:** July 2017 and July 2018 had the highest number of bookings.
  - Total Flights in July: 246,298 flights.
  - By Loyalty Card:
    - Star: 112,219 flights.
    - Nova: 81,772 flights.
    - Aurora: 51,307 flights.

#### 4.1.2 Analysis:
- **Seasonal Trends:** The data indicates a significant increase in bookings during July, suggesting peak travel season.
- **Loyalty Card Performance:** The Star loyalty card members are the most active during peak months.

#### 4.1.3 Visualization: 
- Line chart depicting monthly bookings, sorted chronologically to ensure proper month sequencing, with year as the label.

### 4.2 Correlation Between Flight Distance and Loyalty Points Accumulated
#### 4.2.1 Findings:
- There is a strong positive correlation between average distance traveled and loyalty points accumulated.
- Longer flights result in higher points accumulation.

#### 4.2.2 Analysis:
- **Incentivization Effectiveness:** The loyalty program effectively incentivizes customers to book longer flights.
- **Customer Engagement:** Customers are likely aware of the benefits associated with longer flights, increasing engagement with the loyalty program.

#### 4.2.3 Visualization: 
- Scatter plot with a trend line demonstrating the positive correlation between distance and points accumulated.

### 4.3 Impact of Companion Bookings on Loyalty Points Redeemed
#### 4.3.1 Findings:
- **Highest Points Redeemed:** Groups of 10 companions had the highest average points redeemed at 139.73 points.
- **Comparison to Solo Travelers:** This is 20,750.28 times higher than the average points redeemed by individuals traveling alone (0.67 points).
- **Range of Points Redeemed:** Across all companion bookings, average points redeemed ranged from 0.67 to 139.73.

#### 4.3.2 Analysis:
- **Group Travel Benefits:** The loyalty program significantly benefits group travelers, encouraging customers to book with companions.
- **Redemption Patterns:** Higher points redemption in larger groups suggests customers utilize points more when traveling with others.

#### 4.3.3 Visualization:
- Bar charts showing points redeemed across different numbers of companions.

## 5. Loyalty Segmentation
### 5.1 Customer Segmentation by Loyalty Card Status
#### 5.1.1 Findings:
- **Total Flights by Loyalty Card:**
  - Star: Highest number of flights booked.
  - Nova: Second highest.
 
