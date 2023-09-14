# Project Description
You've done beautifully in the Practicum course, and you've been offered an internship in the analytical department at Y.Afisha. Your first task is to help optimize marketing expenses.

You have:
+ Server logs with data on Y.Afisha visits from June 2017 through May 2018
+ Dump file with all orders for the period
+ Marketing expenses statistics

## Purpose
To identify patterns that determine:
+ How people use the product
+ When they start to buy
+ How much money each customer brings
+ When they pay off

## Task
1. Optimize the data for analysis and make sure each column contains the correct data type.
2. Make reports and calculate metrics:
   + How many people use it every day, week, and month?
   + How many sessions are there per day? (One user might have more than one session.)
   + What is the length of each session?
   + What's the user retention rate?
   + When do people start buying? (use cohort analysis)
   + How many orders do they make during a given period of time?
   + What is the average purchase size?
   + How much money do they bring? (LTV)
   + How much money was spent? Overall/per source/over time
   + How much did customer acquisition from each of the sources cost?
   + How worthwhile where the investments? (ROI)

3. Write a conclusion: advise marketing experts how much money to invest and where.

## Description of the data
The visits table (server logs with data on website visits):
+ Uid — user's unique identifier
+ Device — user's device
+ Start Ts — session start date and time
+ End Ts — session end date and time
+ Source Id — identifier of the ad source the user came from All dates in this table are in YYYY-MM-DD format.

The orders table (data on orders):
+ Uid — unique identifier of the user making an order
+ Buy Ts — order date and time
+ Revenue — Y.Afisha's revenue from the order

The costs table (data on marketing expenses):
+ source_id — ad source identifier
+ dt — date
+ costs — expenses on this ad source on this day

## Techniques used
1. Data cleaning and tranformation
2. EDA
3. Cohort Analysis
4. Summarize Finding
