# Ola Data Analytics Dashboard
-----
## 📌 Project Overview

This project provides a comprehensive analysis of Ola's ride-booking data to solve real-world business problems like high cancellation rates, delivery time optimization, and revenue breakdown. Using a dataset of over **100,000 rows** and **19 columns**, the project demonstrates how to extract actionable insights using **SQL** for data querying and **Power BI** for interactive visualization.

## 🛠️ Tech Stack

  * **Excel:** Initial data cleaning (removing duplicates and handling whitespaces).
  * **SQL (MySQL):** Database creation and solving complex business questions through queries and views.
  * **Power BI:** Building a multi-page interactive dashboard for executive-level reporting.

## 📂 Dataset Details

The dataset contains key ride metrics, including:

  * **Booking Status:** Success, Canceled by Customer, Canceled by Driver, Driver Not Found.
  * **Vehicle Type:** Auto, Bike, Prime Sedan, Prime SUV, Mini, etc.
  * **Metrics:** Ride distance, booking value, customer/driver ratings, and payment methods (UPI, Cash, Card).

## 📊 SQL Analysis

The project addresses 10 critical business questions using SQL:

1.  **Success Rate:** Retrieve all successful bookings.
2.  **Vehicle Performance:** Find the average ride distance for each vehicle type.
3.  **Cancellations:** Get the total count of rides canceled by customers and drivers.
4.  **Customer Loyalty:** List the top 5 customers by the highest number of bookings.
5.  **Rating Analysis:** Find max/min driver and customer ratings.
6.  **Revenue:** Calculate total booking value for successful rides.
7.  **Payment Trends:** Filter rides by payment method (e.g., UPI).
8.  **Incomplete Rides:** List all incomplete rides with reasons (e.g., vehicle breakdown).

## 📈 Power BI Dashboard

The dashboard is split into 5 specialized views to avoid clutter:

1.  **Overall:** Ride volume trends over time and booking status breakdown.
2.  **Vehicle Type:** Performance metrics specific to different ride categories.
3.  **Revenue:** Revenue distribution by payment method and top customers by spend.
4.  **Cancellations:** In-depth analysis of why rides are being canceled.
5.  **Ratings:** Comparative analysis of customer vs. driver ratings.

## 🚀 How to Use

1.  **Data Cleaning:** Use the provided Excel file to clean raw data.
2.  **Database Setup:** Run the SQL scripts in MySQL Workbench to create the `Ola` database and import the `.csv` file.
3.  **Visualizing:** Open the `.pbix` file in Power BI Desktop, connect to your MySQL database (or local CSV), and explore the interactive filters.

-----
