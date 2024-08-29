# ITV-Grands-Hospitality-Management-Project
 Project Description: Hotel performance analysis using MySQL and Power BI for ITV Grands.
Here's a detailed outline for your GitHub README file for the hospitality management project:

---

# ITV Grands Hospitality Management Project

## Project Overview

ITV Grands, a well-established chain of luxury hotels in India, has been facing challenges in maintaining its market share and revenue in the competitive luxury/business hotel category. This project aims to provide comprehensive insights into the performance of ITV Grands' hotels using historical data from May to July 2022, covering four major cities: Mumbai, Delhi, Bangalore, and Hyderabad. The analysis was performed using both **MySQL** for data querying and **Power BI** for visualization.

## Objectives

The main objectives of this project were:
- To analyze revenue, occupancy, and customer satisfaction across different hotels and cities.
- To identify trends, patterns, and potential areas for improvement.
- To provide actionable insights to help ITV Grands regain its market share and improve overall performance.

## Data Description

The data used in this project consists of hotel booking information from May to July 2022. The dataset includes the following key tables:
- **Bookings Data:** Contains detailed information about each booking, including booking status, platform, and revenue generated.
- **Hotel Data:** Information about the different hotels, including location, category (luxury/business), and room details.
- **Customer Data:** Customer demographics and feedback ratings.
- **Revenue Data:** Detailed revenue figures broken down by city, hotel, room type, and booking status.

## Tools Used

- **MySQL:** Used for querying the dataset and performing detailed data analysis.
- **Power BI:** Utilized to create interactive dashboards for visualizing the insights derived from the data.

## Key Insights

### 1. Revenue Analysis
- **Total Revenue:** The total revenue generated over the three-month period was 2 billion INR, with luxury hotels contributing 61.61% and business hotels contributing 38.39%.
- **Top Performers:** The highest revenue was generated by the luxury hotel "ITV Exotica" (320M INR), followed by "ITV Palace" and "ITV City."
- **Booking Status Impact:** Successfully checked-out bookings accounted for 82.46% of the total revenue, while cancellations and no-shows significantly impacted potential revenue.

### 2. Occupancy and Booking Metrics
- **Occupancy Rate:** The average occupancy rate was 57.87%, with Mumbai leading at 24.92% and Hyderabad at 25%.
- **Booking Platforms:** The majority of bookings were made through unspecified platforms (40.9%), with makeyourtrip and direct online bookings following behind.

### 3. Customer Satisfaction
- **Average Rating:** The overall customer rating was 3.60 out of 5, indicating room for improvement. Delhi had the highest average rating (3.8), while Bangalore had the lowest (3.4).

### 4. Cancellation Rate
- **Overall Rate:** The cancellation rate was 24.83%, with Delhi having the highest at 25.2%.
- **Revenue Impact:** Cancellations had a noticeable impact on revenue, highlighting the need for better cancellation management.

### 5. Room Utilization
- **Revenue by Room Class:** The "Elite" room class generated the highest revenue (0.56bn INR), followed by "Premium" and "Presidential" room classes.

### 6. Stable Occupancy, Falling Revenue
- Despite a stable occupancy rate, revenue decreased over time. This indicates that even though hotels were fully booked, they were making less money per booking. Strategies to address this could include adjusting pricing or offering premium services.

## Power BI Dashboards

### Dashboard 1: Overview of Key Metrics
- **Total Revenue:** Displayed along with breakdowns by city, hotel, and room type.
- **Occupancy Rate and Cancellation Rate:** Shown by city and day type to identify patterns.
- **Customer Satisfaction:** Visualized through average ratings by city.

### Dashboard 2: Detailed Revenue and Booking Analysis
- **Revenue by Property and Category:** Highlights top-performing hotels.
- **Booking Platform Analysis:** Shows the distribution of bookings across different platforms.
- **Room Utilization Metrics:** Displays DBRN, DSRN, and DURN to understand booking patterns.

## Conclusion

This project provided ITV Grands with valuable insights into their current performance, identifying areas for improvement in revenue management, customer satisfaction, and booking strategies. By leveraging the findings from this analysis, ITV Grands can implement data-driven strategies to enhance their market position and achieve sustainable growth.

## How to Use This Repository

1. **MySQL Queries:** The SQL scripts used for data extraction and analysis are available in the `SQL` folder.
2. **Power BI Dashboard Files:** The `.pbix` files for the Power BI dashboards are located in the `Power BI` folder.
3. **Documentation:** Detailed documentation of the project, including methodology and step-by-step explanations, can be found in the `Documentation` folder.

