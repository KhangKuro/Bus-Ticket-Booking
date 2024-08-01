# 🚌 Bus Ticket Booking Data Processing and Analysis

## 📋 Table of Contents
1. [Introduction](#introduction)
2. [Data Cleaning and Transformation Steps](#data-cleaning-and-transformation-steps)
3. [Workflow Overview](#workflow-overview)
4. [Top Metrics for Success](#top-metrics-for-success)
5. [Improving Rule Ranking](#improving-rule-ranking)
6. [Tools and Technologies](#tools-and-technologies)
7. [Insights](#insights)
8. [Contact](#contact)

---

## 🌟 Introduction
This project involves processing and analyzing bus ticket booking data using Excel M Code for data transformation and Tableau for data visualization. The primary goal is to maintain data integrity while deriving valuable insights from the dataset.

---

## 🧹 Data Cleaning and Transformation Steps
1. **🔍 Check Data Type:**
   - Verify data types for all columns to ensure consistency.

2. **♻️ Remove Duplicates:**
   - Identify and remove duplicate rows.

3. **🔬 Check Missing Values and Outliers:**
   - Inspect the dataset for missing values and outliers.
   - Use pivot tables for initial observation of data distribution.

4. **📊 Explore Data with Pivot Table:**
   - Create pivot tables to explore data relationships and identify patterns.

5. **🧩 Impute Missing Values Using M Code:**
   - Fill missing values with appropriate values using Excel M code, ensuring no data is dropped.

6. **🔒 Preserve Data Integrity:**
   - Avoid dropping rows to maintain the dataset size (6755 rows).

7. **📁 Split Tables:**
   - Separate the data into different tables based on relevant criteria.

8. **🔗 Connect Tables in Tableau:**
   - Link the tables in Tableau to create a cohesive data model for analysis.

---

## 🔄 Workflow Overview

1. **📥 Data Collection:**
   - Track user interactions and collect booking data, session data, and user feedback using PostgreSQL.

2. **🔧 Data Integration and Transformation:**
   - Use Python to extract data from various sources, clean, and transform it before loading it into PostgreSQL.
   - Perform additional data cleaning and transformation tasks.

3. **🔢 Customer Segmentation:**
   - Use Scikit-learn to implement clustering algorithms and segment customers based on their behavior and attributes.

4. **📈 Data Analysis:**
   - Use SQL queries within PostgreSQL to aggregate and summarize data.
   - Use Python (Pandas, NumPy) for detailed data analysis and statistical computations.
   - Use clustering results to enhance the analysis.

5. **📊 Data Visualization:**
   - Use Tableau to create interactive dashboards and visualizations that help in understanding the booking flow, identifying bottlenecks, and monitoring key metrics.
   - Include customer segments in the visualizations to provide deeper insights into user behavior.

---

## 📊 Top Metrics for Success

1. **📈 Conversion Rate:**
   - The percentage of users who complete a bus ticket booking out of the total users who start the booking process.
   - **Formula:** Conversion Rate = (Number of Completed Bookings / Number of Users Who Initiated a Booking) * 100

2. **⏱️ Time to Book:**
   - The average time it takes for a user to complete a booking from the moment they initiate a search.
   - **Formula:** Time to Book = Average (Booking Completion Time - Booking Initiation Time)

3. **🚪 Drop-off Rate:**
   - The percentage of users who abandon the booking process at various stages (search, selection, payment).
   - **Formula:** Drop-off Rate = (Number of Users Who Abandon the Process at a Stage / Number of Users Who Reach That Stage) * 100

---

## 🚀 Improving Rule Ranking

1. **🔍 Analyze User Preferences:**
   - Use historical booking data and user interaction data to understand which criteria (e.g., price, departure time, bus operator, ratings) are most important to users.
   - **How:** 
     - Perform a correlation analysis between different trip attributes and booking completions.
     - Use machine learning models (e.g., logistic regression, decision trees) to identify the weight of each attribute in the booking decision.

2. **🧪 A/B Testing:**
   - Implement A/B tests to compare the effectiveness of different ranking algorithms.
   - **How:** 
     - Randomly divide users into control and experimental groups.
     - Apply different ranking algorithms to each group.
     - Measure and compare metrics like click-through rate, time spent on the page, and conversion rate.

---

## 🛠️ Tools and Technologies

- **📋 Data Collection and Storage:** PostgreSQL
- **🔧 Data Processing and Transformation:** Python (Pandas, NumPy, Scikit-learn)
- **📈 Data Visualization:** Tableau

---

## 🔍 Insights

### Top Performing Routes and Bus Companies
- **🏆 Top Route:** Hồ Chí Minh to Khánh Hòa (16.96% of total bookings, 1,626 tickets, 458,156,000 VND fare).
- **🚍 Top Bus Company:** ID ZX/uWhvaphDQluCb+boYgAgnU3wOaClinCarURzrCXc (359 bookings, 574 tickets, 171,704,000 VND fare).

### Top Customer Profile
- **👤 Top Customer ID:** o5tLNOVpFJeLXgnq7u4g (3 bookings, 18 tickets, 6,720,000 VND revenue).

### New vs. Returning Customers
- **🆕 New Customers:**
  - iOS: 1,144 bookings, 1,981 tickets, 472,458,000 VND
  - Android: 819 bookings, 1,341 tickets, 318,236,000 VND

- **🔄 Returning Customers:**
  - iOS: 2,882 bookings, 4,243 tickets, 1,001,092,800 VND
  - Android: 1,871 bookings, 2,609 tickets, 589,156,800 VND

### Booking Patterns and Customer Behavior
- **📅 Booking Timing:** 
  - 35.59% book a day in advance (772,504,400 VND)
  - 26.27% book on the day of the trip (515,048,800 VND)

- **💰 Spending Segments:** 
  - Majority spend less than 2 million VND (4,925 bookings, 1,401,278,800 VND)

### Monthly and Seasonal Trends
- **📉 August vs. July:**
  - Revenue decreased by 60.15% (2,380,943,600 VND to 678,417,200 VND)
  - Average revenue per booking decreased by 15.95% (354,518 VND to 314,082 VND)
  - Total bookings dropped by 52.59% (6,716 to 2,160)
  - New customers fell by 59.98% (1,575 to 461)

- **📅 Seasonal Peaks:** 
  - Booking activity peaks in July, especially on Wednesdays, Thursdays, and weekends.

### Preferred Bus Types and Ratings
- **🚍 Bus Types:** 
  - Predominantly sleeper buses, single seat average fare 235,037 VND.

- **⭐ Ratings:** 
  - Most operators receive 3 stars or higher, indicating overall satisfaction.

---

## 📞 Contact

For any queries or further information, please contact:

- **Email:** hbaokhangofficial@gmail.com
- **Phone:** +84 349 429 011

Thank you! 🚍📊
