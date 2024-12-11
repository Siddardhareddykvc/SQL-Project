# SQL-Project
# Call Center Data Analysis

This project involves analyzing data from a call center to gain insights into call patterns, customer satisfaction, and service performance. The data was stored in a MySQL database table named call_center within a database called call_centerdata.

What I Did

1. Data Preparation

Imported the call center data into a MySQL database for analysis.

Cleaned the data:

Ensured all dates were in a consistent format (YYYY-MM-DD).

Replaced empty values in the csat_score (customer satisfaction score) column with NULL.

2. Basic Data Insights

Counted the total number of rows (records) and columns (data fields).

Examined unique values for specific columns such as sentiment, city, and call_center.

Calculated the number and percentage of calls from each city.

3. Call Volume Analysis

Analyzed the number of calls received on different days of the week.

Identified the longest call duration for each day.

4. Customer Satisfaction Analysis

Reviewed the lowest, highest, and average customer satisfaction scores.

Excluded scores of 0 from the average calculation, assuming they were invalid or missing data.

5. Service Performance Analysis

Evaluated how quickly calls were answered at each call center.

Ranked the centers from best to worst based on their response times.

Tools Used

Database Management System: MySQL

Data Analysis Software: Microsoft SQL Server Management Studio (SSMS)

How to Use

Install a SQL database such as SQL Server Express.

Import the provided .sql files into the database.

Run the SQL queries in your database management tool to replicate the analysis.

