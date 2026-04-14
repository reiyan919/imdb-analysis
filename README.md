IMDb Movie Analytics
Revenue, ROI, and Industry Trends
📌 Project Overview

This project explores movie data from the TMDB dataset to analyze key factors that influence movie revenue, profitability, and audience engagement.

The analysis combines Python (EDA) and Tableau (dashboard visualization) to deliver data-driven insights into the film industry.

🎯 Objectives
Identify factors influencing movie revenue
Analyze the relationship between budget and revenue
Evaluate profitability using ROI and profit
Explore genre performance (ratings vs revenue)
Identify top-performing movies and directors
Analyze industry trends over time
📊 Dataset
Source: TMDB (The Movie Database)
Size: ~3,854 movies
Features include:
Budget & Revenue
Ratings & Popularity
Genre, Director, Cast
Release Year

⚠️ Note:

budget = 0 and revenue = 0 are treated as missing values
🛠️ Tools & Technologies
Python:
pandas
NumPy
Matplotlib
Seaborn
Visualization:
Tableau
🔧 Data Preparation
Converted release_year to datetime
Split multi-value columns (genres, cast)
Removed rows with missing financial data
Created new features:
Profit = Revenue − Budget
ROI = (Revenue − Budget) / Budget
Decade grouping for trend analysis
📈 Key Analysis
🔹 Financial Analysis
Strong positive correlation between budget and revenue (~0.69)
ROI highlights that low-budget films can be highly profitable
🔹 Top Performers
Directors like Steven Spielberg and Peter Jackson dominate total revenue
Blockbuster films such as Avatar and Titanic lead the box office
🔹 Genre Insights
Action generates the highest revenue
Drama is the most common genre
Documentary has the highest ratings but lowest revenue
🔹 Inflation Impact
Older movies show significantly higher value when adjusted for inflation
Highlights importance of using adjusted revenue for comparisons
🔹 Trends Over Time
Growth in movie production over decades
Increasing budgets and revenues in modern cinema
Shift toward franchise-driven industry
📊 Dashboard

An interactive dashboard was created using Tableau to visualize:

Budget vs Revenue
Top Movies & Directors
Genre Performance
Revenue Distribution & Trends

👉 ((https://public.tableau.com/views/IMDbMovieAnalyticsRevenueROIIndustryTrends/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link))

🧠 Key Insights
Budget is the strongest predictor of revenue
A small number of blockbuster films dominate the market
ROI provides a better measure of success than revenue alone
Ratings have a weak relationship with revenue
Franchise movies consistently outperform standalone films
🏁 Conclusion

Movie success is driven primarily by budget, franchise strength, and market reach, while ROI reveals that profitability is not limited to high-budget productions. The analysis highlights the importance of combining financial and audience metrics to understand industry performance.
