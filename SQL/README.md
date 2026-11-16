# SQL Analytics Projects

This repository contains two SQL projects that solve real business questions on relational databases: flight operations analysis on an Airline database and sales analysis on the Adventure Works Cycles database.

---

# Project 1: Airline Database Analysis

## Description

**This airline database project provides valuable insights into flight operations and passenger bookings using SQL.**

The AirlineDB models an airline's business across linked tables: Bookings, Tickets, Ticket_flights, Flights, Airports_data, Aircrafts_data, Seats and Boarding_passes. One booking can include several passengers, each with a separate ticket, and each ticket can include one or more flight segments. Using this database, the project analyzes the number of flights departing from each airport in every period of the day (Morning, Afternoon, Evening and Night). It also identifies all booking references where travellers took Airbus flights.

## Skills Used

*Data extraction and analysis, Relational database querying, Conditional aggregation, Multi-table joins, Business problem solving*

## Technologies and Concepts Used

**SQL, INNER JOIN, GROUP BY, ORDER BY, CASE WHEN, EXTRACT (time functions), COUNT, DISTINCT, LIKE pattern matching**

## Queries Solved

| Business Question | Key SQL Concepts |
|---|---|
| Number of flights per departure airport in each period of the day (Morning, Afternoon, Evening, Night) | CASE WHEN, EXTRACT, COUNT, GROUP BY |
| Booking references where travellers took Airbus flights | Multi-table JOINs, DISTINCT, LIKE |

## Final Outcome

The final outcome of this project was a set of optimized SQL queries that show the departure pattern of flights by time of day for each airport and list all bookings made on Airbus aircraft. These results can support flight scheduling and fleet-level analysis.

---

# Project 2: Adventure Works Cycles Sales Analysis

## Description

**This Adventure Works Cycles project provides valuable insights into product sales performance and helps identify where marketing efforts are most and least needed.**

The Adventure Works dataset captures various facets of the business, from sales data and product details to customer demographics and product returns. Using SQL, this project identifies the "blockbuster territory" (the territory with the highest sales volume) for each product subcategory, so marketing effort can be directed away from areas that already perform well. It also reports the total quantity sold for each product category for each year from 2020 to 2022, keeping categories with no sales visible as NULL values.

## Skills Used

*Data extraction and analysis, Sales performance analysis, Data aggregation, Window function analysis, Business problem solving*

## Technologies and Concepts Used

**SQL, Common Table Expressions (CTEs), Window Functions (RANK, PARTITION BY), INNER JOIN, LEFT JOIN, CASE WHEN, EXTRACT (year), SUM, GROUP BY, ORDER BY**

## Queries Solved

| Business Question | Key SQL Concepts |
|---|---|
| Blockbuster territory (highest sales volume) for each subcategory | CTEs, RANK() OVER (PARTITION BY), JOINs |
| Total quantity sold per category for 2020, 2021 and 2022 | LEFT JOIN, CASE WHEN, SUM, EXTRACT |

## Final Outcome

The final outcome of this project was a set of SQL queries that identify the top-selling territory for every product subcategory and show year-wise category sales trends from 2020 to 2022. These results can inform targeted marketing strategies and sales planning.

---

## Tools

SQL (PostgreSQL-style syntax)
