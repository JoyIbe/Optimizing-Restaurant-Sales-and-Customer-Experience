# Optimizing Restaurant Sales and Customer Experience: A Data-Driven Approach to Revenue Growth and Operational Efficiency

## Title: Eatt Restaurant Sales Analysis Report

## Table of Contents

- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Tool and Methodology](#tools-and-methodology)
- [Dashboard](#dashboard)
- [Key Analysis Findings](#key-analysis-findings)
- [Insights from Analysis](#insights-from-analysis)
- [Business Questions and Answers](#business-questions-and-answers)
- [Recommendations](#recommendations)
- [Implementation Plan](#implementation-plan)
- [Limitation](limitation)
- [Link to Viz](#link-to-viz)
- [Conclusion ](#conclusion)

## Overview
Eatt Restaurant is a growing food business that operates multiple locations and offers diverse cuisines, ranging from American and Italian to Japanese and Mexican. With annual revenue of $5.49 billion and a marketing budget of $26.93 million, the restaurant chain aims to optimize sales performance, customer experience, and overall profitability. This analysis provides a data-driven assessment of revenue patterns, customer preferences, reservation trends, and operational efficiency.

## Problem Statement
Stakeholders, including restaurant managers, marketing teams, and investors, seek to address critical challenges such as:
- The relationship between social media engagement and revenue performance.
- Understanding customer behavior across different cuisines and locations.
- Identifying the impact of marketing efforts on sales.
- Evaluating reservation trends to optimize capacity planning.
- Ensuring operational efficiency through service quality and parking availability.

## Tools and Methodology:

### Tools: 

Figma: Used to create the dashboard wireframe

Power Query: I used power query to perform key transformational steps. The dataset initially lacked images, which are essential for enhancing the visual appeal and interpretability of the dashboard. To fulfill this requirement, images were embedded into the dataset using Power Query. This approach ensured that the visualizations were more engaging and provided a clearer representation of key insights for stakeholder.

Dax: I used Dax functionalities generate measures for key metrics and custom visuals.

Power BI: To build the interactive dashboard.

### Method:

Data Cleaning: I carried out major cleaning steps like standardization, removing duplicates, and ensuring accuracy in the provided dataset. I also ensured a backup documentation of cleaning steps.
 
Data Processing: With Power Bi's Dax functionalities, I created calculated measures to show valuable metrics, customized and design visuals to aid clarity in understanding trends.

Data Modeling: Upon creating a new image table, I defined the relationship between tables. Modeling this data allows for multiple tables with lesser column information to speed up processing time, reduce redundancy and increase efficiency.

Data Visualization: Built a three page interactive dashboards that answers stakeholders qustions in detail.

## Dashboard

### Overview Page
<img width="576" alt="Eatt Overview" src="https://github.com/user-attachments/assets/836e293f-fa4d-4db7-a03e-9c0753a7583b" />

## Comparison Page
<img width="578" alt="Eatt Comparison" src="https://github.com/user-attachments/assets/18260286-7a99-4084-8c79-48e6471b8e26" />

## Detail Page
<img width="578" alt="Eatt Detail" src="https://github.com/user-attachments/assets/d1a8ce02-b7b1-4109-acd0-d32e748cf0fc" />

## Key Analysis Findings
1. Revenue Performance by Cuisine:
   - Japanese cuisine generates the highest revenue ($1.26 billion), followed closely by French and Italian cuisines.
   - American cuisine, while popular, has a lower total revenue compared to others.
   
2. Marketing Budget Efficiency:
   - The highest marketing spending is on Italian cuisine ($4.6 million), but it does not generate proportionate revenue.
   - American cuisine has a relatively high marketing budget but lower revenue compared to Japanese or French cuisines.

3. Social Media vs. Revenue:
   - Some restaurants with higher social media engagement generate lower revenue, indicating that engagement alone does not drive sales.
   - Conversely, certain high-revenue restaurants have lower social media presence, suggesting the need for a balanced digital marketing strategy.

4. Reservation Trends:
   - Weekday reservations (244,641) slightly exceed weekend reservations (246,787), highlighting a strong demand on both days.
   - Japanese and French cuisines attract the highest reservations, aligning with their revenue dominance.
   - Downtown locations generally have more reservations than suburban or rural areas.

5. Service Quality & Customer Experience:
   - The overall average service quality score is 5.51, with some variance across cuisines.
   - Parking availability is almost evenly split (49.94% Yes, 50.06% No), potentially affecting customer convenience and satisfaction.

## Insights from Analysis
- Japanese and French cuisines are the strongest revenue drivers and should receive strategic investment for growth.
- Social media engagement does not guarantee higher revenue, but a targeted approach can enhance brand visibility.
- Marketing budgets should be reallocated based on revenue contribution to improve return on investment.
- Parking availability might be a limiting factor in customer footfall, requiring assessment of locations with lower availability.

## Business Questions and Answers
1. Which cuisine generates the highest revenue?
   - Japanese cuisine leads, followed by French and Italian.

2. Does high social media engagement correlate with revenue?
   - Not necessarily. Some high-revenue restaurants have low engagement, indicating other factors drive sales.

3. What is the impact of marketing spend on revenue?
   - Some cuisines receive disproportionate marketing budgets without matching revenue, suggesting inefficiencies.

4. What trends exist in reservations?
   - Weekday and weekend reservations are nearly equal, with Japanese and French cuisines leading in bookings.

5. Does parking availability impact sales?
   - Locations with limited parking may deter customers, affecting revenue and experience.

## Recommendations
1. Optimize marketing budgets to focus on high-revenue cuisines like Japanese and French while reassessing spending on underperforming categories.
2. Enhance digital marketing strategies to convert social media engagement into sales, particularly for low-revenue but high-engagement locations.
3. Improve customer experience by addressing parking constraints and service quality discrepancies.
4. Expand high-performing cuisines by opening new locations or refining menu offerings.
5. Leverage reservation trends to optimize staffing, inventory, and promotional activities.

## Implementation Plan
1. Q1: Conduct a marketing budget audit and reallocate funds based on revenue impact.
2. Q2: Launch targeted social media campaigns focused on conversion rather than just engagement.
3. Q3 Assess parking availability at key locations and explore partnerships for additional spaces.
4. Q4: Enhance service quality by training staff and improving customer feedback mechanisms.


## Limitation
A major limitation of this analysis is the absence of a date column in the dataset. This hindered deeper analysis into the time-series trends of sales performance, making it difficult to assess seasonality, monthly trends, or the impact of specific events on revenue.

## Link to Viz
[Power BI Viz](https://app.powerbi.com/reportEmbed?reportId=03492c66-5942-46e6-a07b-0beeb5a07417&autoAuth=true&ctid=0801c8b7-f6a9-44a2-8891-282fd58fab33)
## Conclusion
This analysis highlights key revenue drivers, marketing inefficiencies, customer behavior trends, and operational challenges. By aligning business strategies with data-driven insights, Eatt Restaurant can maximize profitability, enhance customer experience, and sustain long-term growth.

