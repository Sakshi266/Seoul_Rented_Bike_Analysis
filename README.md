# SEOUL_RENTED_BIKE_BOOKING
This Power BI project analyzes the Seoul Bike Sharing dataset, aiming to understand how environmental and seasonal factors influence the number of rented bikes.
The dashboard provides interactive insights into rental trends, weather conditions, seasonal variations, and working day impacts.
## 🔎 Project Overview

This project explores the Seoul Bike Sharing dataset using Power BI. The dashboard answers questions like:

When and where are bikes most used (hour/day/month/season)?

Which stations have the highest demand and which are underused?

How do weather and holidays affect usage?

What is the typical trip duration and how does it vary by user type?

The goal is to provide actionable insights for operations teams, city planners, and product managers.
## 🗂️ Dataset

Typical columns included (may vary by source):

rental_id / ride_id

ride_date / start_time, end_time

duration (seconds/minutes)

start_station_id, start_station_name

end_station_id, end_station_name

user_type (registered / casual)

temperature, humidity, wind_speed, weather

holiday, weekday, weekend

year, month, hour
## 🛠 Tech Stack

Power BI Desktop (data modeling, Power Query, DAX, visuals)

Optional: Python/R (for preprocessing or advanced stats before import)

Data source: CSV / Excel / Database
## 🚀 Key Deliverables

Power BI .pbix dashboard with interactive visuals

Cleaned dataset or Power Query steps saved in .pbix

README + folder structure for reproducibility
## 📊 Dashboard Pages & Visuals

Overview (Landing)

KPI cards: Total rides, Avg duration, Peak hour, Registered vs Casual ratio

Time-series chart: Daily/Monthly rides

Temporal Analysis

Hourly heatmap (hour vs day of week)

Monthly seasonality chart

Trend lines with slicers for year/user type

Spatial / Station Analysis

Top start and end stations (bar charts)

Station demand table with % change, capacity notes

If coordinates available — map visual (bubble size by rides)

Weather & External Factors

Rides vs Temperature / Rain / Humidity scatter charts

Holiday vs Non-holiday comparison

User Behavior

Trip duration distribution (histogram)

Registered vs Casual comparison (charts & cross-filtering)

Recommendations / Actionable Insights

Suggested station rebalancing windows

Hours needing higher availability/staffing

Weather-aware demand predictions (if modeled)
## 🔄 Data Cleaning & Power Query Steps

Parse date/time into Date, Hour, DayOfWeek, Month, Year

Convert duration to minutes and create duration_category (short/medium/long)

Fill or drop missing station names / IDs; standardize station names

Flag holidays and weekend days (join with calendar table)

Merge weather data on date/hour (if separate)


