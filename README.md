 SQL Music Store Analysis

## Project Overview
This project involves exploratory data analysis of the Chinook database, 
a relational dataset modeled after a digital music store. The database 
contains 11 tables including customers, invoices, tracks, artists, albums, 
and genres. A total of 8 SQL queries were written to extract meaningful 
business insights from the data.

## Tools & Technologies
- SQL
- DB Browser for SQLite

## Objectives
- Analyze customer distribution across countries
- Calculate total revenue by region
- Identify top spending customers
- Rank best selling genres, artists, and tracks
- Explore monthly revenue trends

## Queries & Key Findings

*Query 1: Customer Data Overview*
Retrieved the first 10 records from the Customer table to understand 
the dataset structure.

*Query 2: Customer Distribution by Country*
The USA had the highest customer count at 13, followed by Canada (8), 
France (5), and Brazil (5) across 24 countries total.

*Query 3: Revenue by Country*
Aggregated total invoice amounts by billing country to identify the 
highest revenue generating regions.

*Query 4: Top 10 Customers by Spending*
Joined the Customer and Invoice tables to rank customers by total 
purchase amount.

*Query 5: Best Selling Genres*
Joined four tables to count total tracks sold per genre and rank 
by popularity.

*Query 6: Top Selling Artists*
Identified the top 10 artists by total sales volume using multi-table joins.

*Query 7: Monthly Revenue Trend*
Extracted month from invoice dates to analyze revenue patterns over time.

*Query 8: Best Selling Tracks*
Ranked the top 10 individual tracks by total units sold.

## SQL Concepts Demonstrated
- SELECT, FROM, WHERE
- GROUP BY, ORDER BY, LIMIT
- JOIN (multi-table joins)
- Aggregate functions: COUNT, SUM, ROUND
- String functions: STRFTIME
