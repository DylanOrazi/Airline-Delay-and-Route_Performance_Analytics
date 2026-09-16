# Airline Delay and Route Performance Analytics

## Overview

A full data analytics project focused on airline delays, route performance, airport trends, cancellations, and operational reliability.

The project starts with 8,000 synthetic flight records containing intentional data-quality problems such as duplicate rows, inconsistent airline names, missing values, invalid airport codes, repeated flight IDs, and delay outliers.

After cleaning and validation, the final dataset contains **7,965 flight records**.

The project uses:

- Python
- pandas
- SQLite / SQL
- Power BI
- DAX
- Excel

---

## Project Workflow

The project demonstrates an end-to-end analytics process:

1. Raw data review
2. Data cleaning and validation
3. Cleaned dataset creation
4. SQLite database setup
5. SQL analysis
6. Python exploratory data analysis
7. Chart creation
8. Power BI data modeling
9. DAX measure creation
10. Dashboard development

---

## Data Cleaning

Major cleaning and validation tasks included:

- Removing exact duplicate rows
- Standardizing airline names
- Filling selected missing values
- Validating airport codes
- Flagging invalid routes
- Standardizing cancellation codes
- Flagging delay outliers
- Converting time fields
- Creating analytical columns
- Reviewing repeated flight IDs

### Final Dataset

- Raw rows: 8,000
- Cleaned rows: 7,965
- Unique flight IDs: 7,960
- Repeated flight ID records: 5
- Airlines: 10
- Origin airports: 28
- Destination airports: 25
- Routes: 620

---

## Key Flight Metrics

- On-time flights: 2,961
- Delayed flights: 4,842
- Cancelled flights: 127
- Diverted flights: 35
- On-time rate: 37.18%
- Delay rate: 60.79%
- Cancellation rate: 1.59%

---

## Python Analysis

Python was used for:

- Data cleaning
- Validation
- Grouped analysis
- Summary exports
- Exploratory analysis
- Chart generation

Example outputs include:

- Airline performance summaries
- Airport performance summaries
- Monthly trend summaries
- Segment analysis
- Eight exported charts
- EDA text summary

---

## SQL Analysis

SQLite and SQL were used for:

- Data validation
- Record-count checks
- Duplicate ID review
- Missing-value review
- Airport and route validation
- Airline performance analysis
- Airport performance analysis
- Route analysis
- Monthly trend analysis
- Data-quality checks

Reusable SQL views were also created for airline, airport, route, and overall flight analysis.

---

## Power BI Dashboard

The Power BI solution uses a star-schema-style model with:

- FactFlights
- DimAirline
- DimOriginAirport
- DimDestinationAirport
- DimRoute
- DimDate

The dashboard contains five pages:

1. Executive Overview
2. Airline Performance
3. Airport and Route Analysis
4. Delay and Cancellation Analysis
5. Monthly Trend Analysis

---

## DAX Measures

DAX measures were created for:

- Total flights
- On-time rate
- Delay rate
- Cancellation rate
- Average delays
- Median delays
- Route validity
- Airline rankings
- Route rankings
- Previous-month comparisons
- Moving averages
- Severe and extreme delay rates

---

## Key Findings

Some major findings from the synthetic dataset include:

- Delayed flights were the largest flight-status category.
- Overall on-time performance was below 40%.
- Delta Air Lines had the strongest on-time performance.
- JetBlue Airlines had the weakest on-time performance.
- Evening and night departures showed higher delay rates.
- Summer months showed weaker on-time performance.
- Higher-risk routes generally performed worse.
- Invalid route records were retained and flagged instead of deleted.
- Five repeated flight IDs remained after exact duplicate removal.

---

## Project Structure

```text
Data/
    Raw/
    Cleaned/

Python/

Database/

SQL Queries/

Power BI/

Exports/
    Python Charts/
    Python Analysis/
    SQL Results/

Screenshots/
