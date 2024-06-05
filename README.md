# Cyclistic Bike Sharing Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Phase](#exploratory-phase)
- [Data Analysis](#data-analysis)
- [Result of Analysis](#result-of-analysis)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

## Project Overview

### This project aims to understand how the two different customers (member and casual riders) uses bike differently. At the end of this analyis, it will help to uncover patterns, trends which will eventually help in converting casual riders to member riders for more profitability.

## Data Sources

### The data was gotten from Coursera Capstone Project. The data set was downloaded as a zip file before being extracted and stored as a csv file.

## Tools Used

* Excel
  1. It was used for data cleaning.
  2. It was used for data analysis.
  3. It was used for data visualization.

## Data Cleaning and Preparation
The following task was initiated during this phase
- Removal of blanks
- Reformating to remove errors

## Exploratory Phase
The following question was asked to help understand our problem that is to be solved
- What is the total number of customers?
- Which bike is mostly used by customers?
- What day of the month does customer like to start riding and which one is the least?
- What is the most used day?
- What is the average ride length?

## Data Analysis
During the analysis phase using excel, several functions were used to reach conclusions. They include:
- The subtraction function ```=(D2-C2)``` was used to know the ride length
- The Weekday function ```
=weekday(C2,1)```
was used to convert datetime data entry to day. However, ```
=text(C2,"dddd")``` was used to return day as sunday through monday.
- The mode function was used to know the most occuring day used by customers ```=mode(C2:C10)```
- The average function ```=average(E2:E10)``` was used discover the average ride length used
- The maximum function was employed to discover the max ride length ```=max(E2:E10)```
- Merging of files was performed using the power query.
- A pivot table was initiated through the power query for a quick analyis and creation of visuals.

## Result of Analysis
1. Casual riders makes use of weekends most especially saturdays followed by sundays while members steadily uses bikes across all days but most especially on Tuesdays and least on sundays.
2. Both riders prefer using classic bike as ride type.
3. Casual riders commands the highest average ride length.
4. Members contribute a larger percentage of bikes used during this period.

## Recommendations
1. Incentives should be provided to casual riders to help attract them to becoming members.
2. More awareness should be made most especially as regards classic bikes as this will draw casual riders to it the more.
3. Programs and events should be initiated during weekends, this will help casual riders to feel welcomed to the company.

## Limitations
This project is limited to the following;

1. The analyis is based on a year period running from December 2020 to November 2021.
2. A larger chunk of empty cells were deleted which could limit the accuracy of this analysis.

## References
- Coursera
- Google
- Youtube channels
