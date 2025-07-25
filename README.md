# Uber-fares-dataset-analysis

Course: Introduction to Big Data Analytics
Instructor: Eric Maniraguha
Assignment Date: July 23, 2025
Name: Uwmamwezi Denyse ID: 27976
1. ✨ Introduction

This project aims to analyze Uber ride fare data to extract meaningful business insights. The main objectives include understanding fare distribution, identifying busy ride periods, exploring time-based patterns, and building an interactive dashboard using Power BI. These insights are intended to support decision-making in pricing strategy, driver allocation, and service planning.

2. 🔬 Methodology

Data Collection:

Source: uber.csv (Uber ride data from Kaggle)

Tools Used:

Python (Pandas, NumPy, Matplotlib)

Power BI (for visualization and dashboard creation)

Data Preparation Steps:

Removed null and duplicate values

Cleaned invalid entries in coordinates and fare_amount

Created new features:

hour, day, month, day_of_week from datetime

Fare_Bin (binned fare ranges for histogram)

Data Export:

Final cleaned dataset exported as enhanced_uber_features.csv for use in Power BI

3. 📊 Analysis

Fare Distribution:

Histogram and Box Plot were created

Most common fare range: $5 - $15

Outliers (>$50) identified using box plot

Time-Based Patterns:

Ride counts peak between 7 AM - 9 AM and 5 PM - 7 PM

Fewer rides on weekends and late nights

Weekly & Monthly Trends:

Mondays and Fridays have the highest ride demand

Seasonal peaks observed in summer months

4. 📊 Results

~70% of fares fall under $20

Clear peak demand during work commute hours

Surge fare effects evident in outlier values

Geographic ride clusters (if mapped) visible in city centers

5. 🌐 Conclusion

This analysis reveals strong patterns in Uber fare distribution and rider behavior. The interactive Power BI dashboard supports exploration by time, fare range, and ride count. Outliers in fare amounts and peak usage periods offer actionable business insights.

6. 💼 Recommendations

Dynamic Pricing: Increase fares during peak hours and high-demand days

Driver Availability: Incentivize shifts during early mornings, evenings, and weekends

Marketing: Offer promos during off-peak hours to boost ride volume

Planning: Use fare bins and time-based data to forecast demand more accurately
