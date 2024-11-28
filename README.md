# AIRBNB Booking Analysis Using Python

Table of Contents
1. Introduction to Airbnb
2. About the Dataset
3. Python Libraries Used
4. Project Workflow
5. Purpose of the Analysis
6. Project Summary
7. Business Questions
8. Business Conclusion

# 1. Introduction to Airbnb-
  Airbnb is a global platform for short-term stays and experiences. Founded in 2008 in San Francisco, California, by Brian Chesky, Joe Gebbia, and Nathan Blecharczyk, it began as a way to help people rent out extra space in their homes to travelers.

 Key Features:

1.	Accommodations: A wide variety of listings, including private homes, apartments, treehouses, boats, and even castles.

2.	Experiences: Locals can host activities, such as guided tours, cooking classes, or outdoor adventures.

3.	Long-Term Stays: Caters to travelers seeking month-long or extended accommodations.

4.	Flexibility: Hosts can list entire homes, private rooms, or shared spaces. Guests can filter searches based on preferences like price, location, and amenities.

5.	Global Reach:
    - Available in 190+ countries and over 100,000 cities.
    - Supports multiple languages and currencies.
    - As of 2024, Airbnb has facilitated stays for millions of travelers worldwide.

6.	Business Model:
    -	Revenue: Airbnb charges service fees:
    -	Host fee: Typically around 3% of the booking subtotal.
    -	Guest fee: Usually between 10% - 14% of the booking cost.
    -	No Property Ownership: Acts as a platform connecting hosts and guests without owning real estate.

7.	Core Values:
    -	Belong Anywhere	: Encourages global connections and cultural exchange.
    -	Sustainability: Advocates for responsible travel and community building.
    -	Authenticity: Focuses on offering real, local experiences rather than standardized hospitality.

8.	Impact:
    -	Created new income opportunities for hosts.
    -	Faces challenges with regulatory compliance, including concerns about housing shortages and competition with hotels.
    -	Continues to innovate with features like "Airbnb Categories" and advanced search filters for unique stays.

# 2. About the Dataset – Airbnb Bookings NYC 2019
    •	Number of records: 48,895
    •	Number of attributes: 16
    •	Data Characteristics: The dataset includes both categorical and numeric values, providing a diverse range of information about the listings.
    •	Purpose: This dataset is useful for analyzing trends and patterns in the Airbnb market in New York City, as well as gaining insights into the preferences and behavior of Airbnb users in the area. It contains information about Airbnb bookings in New York City in 2019.
 
 # 3. Python Libraries Used
    To conduct the exploratory data analysis (EDA), the following Python libraries were utilized:
    •	Pandas: For data manipulation and analysis.
    •	NumPy: For numerical operations.
    •	Matplotlib: For creating static, interactive, and animated visualizations.
    •	Seaborn: For statistical data visualization.
    •	Warnings: For control warning messages.
    •	Folium: For creating interactive maps.

# 4. Project Workflow
    •	Importing Libraries
    •	Loading the Dataset
    •	Exploring the Dataset
    •	Data Cleaning and Manipulation
    •	Handling Outliers
    •	Data Visualization
    •	Addressing Business Questions
    •	Conclusion

# 5. Purpose of the Analysis
  The primary aim of this analysis is to understand the factors that influence Airbnb prices in New York City and to identify patterns across various variables. The insights generated from this analysis will be valuable for both travelers and hosts in the city, as well as providing critical information for Airbnb's business strategy.

# 6. Project Summary
    •	Analysis Objective: Understanding the factors that influence Airbnb prices in New York City and identifying patterns among various variables.
    •	Data Preparation: This project involved exploring and cleaning the dataset to prepare it for analysis. The exploration process included identifying data types, missing values, and     value distributions. The cleaning process addressed inconsistencies, errors, and duplicates, ensuring high-quality data for analysis.
    •	Data Exploration: Following data cleaning, we conducted exploratory analysis to summarize and visualize the data, identifying patterns and trends. This involved developing         
    relationships between different variables and uncovering underlying causes of specific trends.
    •	Visualization Insights: Various graphs and charts were created to visualize the data, with observations documented alongside each visualization to enhance understanding. Key 
    findings included the influence of minimum nights, the number of reviews, and host listing counts on pricing, as well as significant variations in availability across neighborhoods.
    •	Future Implications: The observations and insights derived from this analysis will inform future research and decision-making related to Airbnb, offering valuable information to 
    both travelers and hosts.

# 7. Business Questions
    1.	What is the distribution of Airbnb booking prices in New York City, and how can this be represented by a histogram?
    2.	How many listings are available in each neighborhood group, and how can this be visualized using a bar plot?
    3.	What is the average price of listings in each neighborhood group, and how can this be illustrated using a line chart?
    4.	Which neighborhoods have the highest number of listings, and how can this be depicted using a bar plot?
    5.	Who are the top hosts with the most listings, and how can this be represented using a bar chart?
    6.	How many active hosts are there per location, and how can this be shown using a line chart?
    7.	What is the average minimum price in different neighborhoods, and how can this be visualized using scatter and bar charts?
    8.	What are the total counts of each room type available on Airbnb?
    9.	How do stay requirement counts by minimum nights appear, and how can this be illustrated using a bar chart?
    10.	What are the total reviews by each neighborhood group, and how can this be represented using a pie chart?
    11.	How many maximum reviews does each neighborhood group have, and how can this be visualized using a pie chart?
    12.	What is the count of each room type in the entire NYC area, and how can this be shown using multiple bar plots?
    13.	How do price variations in NYC neighborhood groups appear, and how can this be illustrated using a scatter plot?
    14.	What are the best location listings for travelers and hosts?
    15.	How can pair plot visualization be utilized to analyze the data?

# 8. Business Conclusion
1.	Manhattan and Brooklyn have the highest demand for Airbnb rentals, as evidenced by the large number of listings in these neighborhoods. This could make them attractive areas for hosts to invest in property.
2.	Manhattan is world-famous for its parks, museums, buildings, town, liberty, gardens, markets, island and also its substantial number of tourists throughout the year, it makes sense that demand and price both high.
3.	Brooklyn comes in second with significant number of listings and cheaper prices as compared to the Manhattan: With most listings located in Williamsburg and Bedford Stuyvesant two neighborhoods strategically close to Manhattan tourists get the chance to enjoy both boroughs equally while spending less.
4.	Williamsburg, Bedford-Stuyvesant, Harlem, Bushwick, and the Upper West Side are the top neighborhoods in terms of listing counts, indicating strong demand for Airbnb rentals in these areas.
5.	The average price of a listing in New York City is higher in the center of the city (Manhattan) compared to the outer boroughs. This could indicate that investing in property in Manhattan may be more lucrative for Airbnb rentals. But Manhattan and Brooklyn have the largest number of hosts, indicating a high level of competition in these boroughs.
6.	The data suggests that Airbnb rentals are primarily used for short-term stays, with relatively few listings requiring a minimum stay of 30 nights or more. Hosts may want to consider investing in property that can accommodate shorter stays in order to maximize their occupancy rate.
7.	The majority of listings on Airbnb are for entire homes or apartments and also Private Rooms with relatively fewer listings for shared rooms. This suggests that travelers using Airbnb have a wide range of accommodation options to choose from, and hosts may want to consider investing in property that can accommodate multiple guests.
8.	The data indicates that the availability of Airbnb rentals varies significantly across neighborhoods, with some neighborhoods having a high concentration of listings and others having relatively few.
9.	The data indicates that there is a high level of competition among Airbnb hosts, with a small number of hosts dominating a large portion of the market. Hosts may want to consider investing in property in areas with relatively fewer listings in order to differentiate themselves from the competition.
10.	The neighborhoods near the airport in Queens would have a higher average number of reviews, as they are likely to attract a lot of tourists or visitors who are passing through the area. The proximity to the airport could make these neighborhoods a convenient and appealing place to stay for travelers for short-term stay with spending less money because. The price distribution is high in Manhattan and Brooklyn.


## THANK YOU
