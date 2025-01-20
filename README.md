# Comprehensive Analysis of buyers of Bike business

## Table of Content 
- [Project Overview](#project-overview)
- [Dataset Source](#dataset-source)
- [Data Exploration](#data-exploration)
- [Data Cleaning](#data-cleaning)
- [Tools Used](#tools-used)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Result](#result)
- [Recommendations](#recommendations)
- [Limitations](#limitations)


## PROJECT OVERVIEW 

Analyze the dataset of bike buyers to uncover insights into customer demographics, location, and economic status, and gain a comprehensive understanding of bike buyers' purchasing behavior to inform targeted marketing and sales strategies and inventory management.


## Dataset SOURCE
The dataset contains information on bike buyers, including demographics, and potentially other relevant factors.
Data Source: Alex the Analyst GitHub


 ## Data Exploration and Cleaning

 ## DATA EXPLORATION 
 The dataset includes the following about buyers
 - ID
 - Marital Status
 - Gender
 - income
 - Occupation
 - Education
 - Number children
 - Number of cars owned
 - if the house is owned or not
 - Age of buyer
 - commute distance
 - Region
 - if the buyer purchased a bike or not

At a glance at the dataset, the gender column has "M" and "F" as male and female respectively, and the marital status also has "M" and "S" as Married and single, this will pose a challenge during analysis.
The data has no missing cells and therefore seemed okay at a glance.

Filter tool was used to understand the data further, and the distance commute column has 10+ miles following 0-1 mile, which doesn't look right, 1-2 miles was supposed to follow.
The age column seems a lot for analysis and will need to be grouped.

## DATA CLEANING
- The dataset was searched for duplicate data and 26 duplicates were found and removed.
The age was grouped using 10-year intervals. Starting from = 25, the age was grouped into "young Adults, adults, mature adults, adults, young adults, senior citizens, old, etc." using the "IFS function."
Using the find-and-replace tool, the "M" and "S" in the marital status were replaced with "Married" and "Single," respectively.
- The "M" and "F" in the gender column were changed to Male and Female using the find and replace tool.

## TOOLS USED
Excel was used for exploration, cleaning, analysis, and visualization.

## EXPLORATORY DATA ANALYSIS 
Customer demography was analyzed against the economic situation and the buyers' purchasing behavior, and the following was discovered.
1. Generally, the average income of married buyers is slightly higher than that of single buyers. more married people buy bikes than single people.
2. Men earn more income than women, and the number of buyers who have purchased bikes is much higher than that of those who have not in both genders; however, the number of male bike buyers is higher than the number of female bike buyers.
3. There is a significant relationship between level of education and income level, the higher the level of education the higher the income of buyers, same with occupation type and income level, buyers on the management level top the list with income followed by Professionals, and manual earning the lowest.
4. The income of buyers affects their buying behavior.
5. Buyers who commute 10+ Miles with higher income seems to buy more bikes while those who commute 0-1 miles buy fewer bikes.
6. Buyers from the Pacific earn more than the other regions and thus purchase more bikes than the other regions.

## RESULTS

  
