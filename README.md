# Instagram Liked Posts Analysis

Serdar ÖZCAN - CS210 Course Project

## Overview

This project delves into the analysis of liked post data from my Instagram account, aiming to uncover insights into user behavior, preferences, and engagement patterns. The analysis involves parsing HTML data from the "liked_posts.html" file, creating visualizations, and applying machine learning techniques for predictive modeling.

## Contents

1. **Data Parsing and Preprocessing**
   - Read and parse HTML content using BeautifulSoup.
   - Create a DataFrame containing user information and the date of liked posts.

2. **Exploratory Data Analysis (EDA)**
   - Visualize monthly, daily, and hourly likes to identify patterns.
   - Analyze likes based on user, season, and day of the week.
   - Identify top users and visualize their engagement.
   
3. **Machine Learning Predictive Modeling**
   - Use RandomForestRegressor to predict the number of likes based on features like day of the week and hour of the day.
   - Evaluate the model's performance and visualize actual vs. predicted values.

4. **Time-Series Analysis**
   - Apply time-series forecasting models like ARIMA to predict future likes.

5. **Conclusion and Insights**
   - Summarize key findings and insights from the analysis.
   - Provide recommendations for improving user engagement.

## Results
- I displayed the total likes by month in each month of the year. I liked the most in June 2021.
- Divided into days, I found that I liked the most on Mondays.
- I saw that I liked the most between 8 and 10 in the morning.

- In addition, I displayed the distribution of likes for the photos of the 5 users whose posts I liked the most, according to seasons. Additionally, I displayed the distributions broken down by 7 days and hours of a day.

- I displayed the total number of likes of the 5 users whose posts I liked most.

- I analyzed my total number of likes according to weekdays and weekends. I saw that there was more on weekend days and Monday than other days.

- For each of the years 2021, 2022 and 2023, I displayed the 5 users whose posts I liked the most and in which month in that year I liked their posts more.

- At the same time, I identified the 5 users I liked the most, separately for these 3 years, according to those years.

- I determined the average number of likes on a yearly, monthly and daily basis.

- I identified the names of the 20 users I liked the least, and also identified the oldest likes among the people I liked the least.
   
- Finally, I got simple outputs by using random forest regression for classification and ARIMA models for time series analysis.
