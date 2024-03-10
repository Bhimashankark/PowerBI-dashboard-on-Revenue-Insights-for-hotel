# Revenue Insights forHospitality Management


## INTRODUCTION

Revenue generation is the way or manner in which a company sells itself and its products to the public to make money. It is a strategic operation that touches every part of an organization; it is not just sales or marketing. In the hospitality domain, revenue is generated through hotel room rentals, meeting space occupancy, and sales of food or beverages. Businesses face a period of growth and decline, and the hospitality industry is no exception. One thing is certain and phenomenal, the hospitality industry lives and dies by its customers. Good customer service can be a revenue generator for a hotel. Focusing on small details can mean the difference between remaining stagnant or increasing profitability. Small things add up.

This document presents the analysis of hotel data for AtliQ Grands, from May 2022 — June 2022. This will enable us to gain insights into various aspects of hotel management, including, customer ratings, occupancy rates, revenue, and bookings. This analysis was performed using Power BI, a powerful data visualization and analytics tool.

## PROBLEM STATEMENT

AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share revenue in the luxury/business hotels category.

Objective: To provide AtliQ Grands with insights from their historical data to regain their market share and revenue.

## SKILLS DEMONSTRATED

This project exposed me to learning a lot using Microsoft Power BI.

· Multiple complex DAX formulas and Functions.

· Calculated columns

· Data Extraction, Cleaning, and Transformation (ETL)

· Data Modelling

· Data Visualization

## DATA TRANSFORMATION

The dataset comprises five CSV files, three dimension tables, and two fact tables. The data was cleaned and transformed using Power Query in Power BI to ensure accuracy and consistency. Data cleaning steps involved;

· Correct data type for columns.

· Replaced incorrect dates with the correct date.

## DATA MODELING

The data model in Power BI consists of five tables:

dim_date: Contains full date information about dates including day type (weekend or weekday), month, and week number (W19 — W32). dim_hotels: Stores identity number of the hotel, property name, category it belongs to (luxury/business), and the city it’s located. dim_rooms: Includes room id and room class. fact_bookings: Stores information about bookings including booking dates, booking platforms, number of guests, revenue, check-in, and checkout dates. fact_aggregrated_bookings: Includes successful bookings, hotel id, and capacity. The dimension tables (with the prefix “dim”) have a matching id in the fact tables (with the prefix “fact”). This modeling produces a one-to-many relationship.

![data modelling](https://github.com/Bhimashankark/PowerBI-dashboard-on-Revenue-Insights-for-hotel/assets/124131684/73a28dbf-0278-4f26-b043-f572c9d683dd)

## VISUALIZATION

![dashboard](https://github.com/Bhimashankark/PowerBI-dashboard-on-Revenue-Insights-for-hotel/assets/124131684/4369692b-e0fc-459e-9ce5-66c8b92b3da3)

From the dashboard, the key metrics are at the top.

Note: RevPar -Revenue Per Available Room, DSRN - Daily Sellable Room Nights/per night, ADR - Average Daily Rate/Amount per room, DBRN -Daily Booked Room Nights/per night, and DURN - Daily Booked Room Nights/per night, Realization% - The ratio of utilized rooms and booked rooms per night, Occupancy% - Total number of occupied rooms out of the available.


Helper Document: Week-on-Week (WoW)  Week-on-Week (WoW) is a type of business metric that measures changes in a specific variable over a period of one week compared to the previous week. It is a common way of tracking business performance over time and is particularly useful for analyzing trends and identifying areas where improvements can be made.

 Here are the metrics for which we found the WoW change% 

1. Revenue WoW change %: To get the revenue change percentage week over week. 
2. Occupancy WoW change %: To get the occupancy change percentage week over week. 
3. ADR WoW change %: To get the ADR (Average Daily rate) change percentage week over week. 
4. RevPAR WoW change %: To get the RevPAR (Revenue Per Available Room) change percentage week over week. 
5. Realisation WoW change %: To get the Realisation change percentage week over week. 
6. DSRN WoW change %: To get the DSRN (Daily Sellable Room Nights) change percentage week over week. 

## RECOMMENDATIONS

The rule of demand and supply and price elasticity is different for the travel, tourism, and hospitality industry. Therefore, the hotel should leverage dynamic pricing to increase revenue generation and increase prices for peak days and weekends.

Consider differential pricing strategies for their offline booking platforms by implementing targeted marketing campaigns/promotions to boost bookings and in turn increase revenue.

AtliQ Grands should pay more attention to customer reviews and ratings and focus on improving customer satisfaction further by addressing critical areas identified in customer reviews.

Explore opportunities to increase direct bookings through the hotel’s website to reduce dependence on other online platforms.

## CONCLUSION

The data analysis performed using Power BI has provided valuable insights into various aspects of hotel management for AtliQ Grands Hotel. The findings and recommendations can help optimize operations, enhance customer satisfaction, and drive revenue growth. Regular monitoring and analysis of key metrics will ensure continued success in the hotel. 
