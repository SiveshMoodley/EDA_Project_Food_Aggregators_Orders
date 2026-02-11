# FoodHub Orders Optimisation Exploratory Data Analysis

## Project Overview
- Performed end-to-end exploratory data analysis (EDA) on an online food delivery dataset to help a food aggregator optimise operations and customer experience
- Analysed demand patterns across cuisines, pricing, and weekdays vs weekends to identify high-value segments and revenue opportunities
- Evaluated delivery and preparation time distributions to uncover operational bottlenecks and service delays
- Generated actionable business recommendations including targeted cuisine promotions and strategies to reduce fulfillment time variability and increase revenue

## Full Project Report Code
**View the full HTML Report Code at:**
https://siveshmoodley.github.io/EDA_Project_Food_Aggregators_Orders/

> The link above renders the complete Exploratory Data Analysis as an html report.  
> GitHub’s file viewer cannot display large HTML notebooks, so please use the link above.

## Code and Resources Used
Python Version: 3.10

Packages: pandas, numpy, matplotlib, seaborn

Python Requirements: pip install -r requirements.txt

## Dataset
Source: MIT Professional Education

Type: Educational / Synthetic Dataset

The dataset represents simulated order records from a food delivery aggregator similar to platforms like Uber Eats or DoorDash. The data information includes:
- Order ID
- Customer ID
- Restaurant Name
- Cuisine Type
- Order Cost
- Weekday or Weekend Order
- Order Rating
- Food Preparation Time
- Delivery Time

The data is intended for learning and exploratory analysis, not for commercial decision-making. No personal or real customer information is included.

## Data Cleaning
- Validated data types, checked for duplicates, and handled missing values in the rating field by treating “Not given” as a separate category rather than dropping records
- Inspected outliers and distributions for cost, preparation time, and delivery time, ensuring values were realistic before analysis

## Exploratory Data Analysis
- Conducted univariate analysis of numerical variables (cost, preparation time, delivery time) to assess distributions, ranges, and potential outliers
- Performed univariate analysis of categorical features (cuisine type, day of week, ratings) using value counts to profile demand patterns
- Undertook bivariate and multivariate analysis to explore relationships between pricing, fulfillment times, and customer ratings

## Analysis Evaluation
- The analysis identified clear differences in demand by cuisine and day of week, indicating opportunities for targeted promotions and capacity planning
- Delivery and preparation times showed consistent ranges, but variability suggests potential to improve operational efficiency and customer experience
- A large proportion of orders lacked ratings, limiting the ability to fully assess satisfaction and highlighting the need for better feedback collection
- See full detailed conclusions and recommendations in the report linked above
- Findings are based on an educational, likely synthetic dataset, so conclusions should be treated as directional rather than predictive
