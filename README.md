## BrightTV Viewership Analysis
## Project Overview

This project analyzes BrightTV user and viewership data to uncover insights into user behavior, content consumption patterns, and key drivers of engagement. The goal is to provide data-driven recommendations to support the growth of BrightTV’s subscription base.

## Objectives
Understand user behavior and viewing patterns
Identify factors influencing content consumption
Highlight high-performing content and regions
Recommend strategies to increase engagement and subscriptions
## Dataset Description
1. user_profile
UserID
Name, Surname, Email
Gender
Race
Age
Province
2. viewership_1
UserID
Channel2
RecordDate2 (UTC)
Duration (HH:mm / mixed formats)
## Data Cleaning & Preparation
Handled missing values using COALESCE()
Converted Duration into seconds for accurate aggregation
Adjusted timestamps from UTC to South African time (UTC +2)
Created Age Groups for segmentation
Managed inconsistent formats (e.g., Excel-based time values)
## Analysis Performed
## User Distribution
Analyzed number of users by province
Identified high-engagement regions
## Content Performance
Measured total watch time per channel
Identified top-performing content
## Time-Based Trends
Analyzed viewership by day of week
Identified peak and low consumption periods
Evaluated hourly viewing patterns
## Demographic Insights
Segmented users by age group and gender
Measured engagement across demographics
## Tools & Technologies
SQL (Data cleaning, transformation, analysis)
Excel (Data visualization)
Canva (Presentation design)
Miro (Project planning and workflow design)
## Key Insights
A small number of channels drive the majority of watch time
User engagement is concentrated in specific provinces
Viewership peaks at certain hours and varies across days
Different demographic groups show different consumption patterns
## Recommendations
Invest in and expand high-performing content
Target high-engagement regions with marketing campaigns
Boost low-consumption days with promotions and content releases
Personalize content strategies based on user demographics
Align content releases with peak viewing hours
## Visualizations

## (Include screenshots of your Excel charts here)

Users by Province
Watch Time by Channel
Usage by Day and Hour
Demographic Analysis

## Learnings
Handling real-world messy data (NULLs, inconsistent formats)
Writing efficient SQL queries for analysis
Translating data insights into business recommendations
Building end-to-end data analysis projects
