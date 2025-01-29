# COVID Data Visualizations using Looker Studio

## Overview
This project visualizes COVID-19 data using **Google Looker Studio** and **BigQuery**. The dataset was uploaded to BigQuery and then used to create insightful visualizations based on various aspects of COVID-19 data, such as cases, deaths, vaccinations, and more. The goal is to provide a clear understanding of global and regional COVID trends.

The following visualizations are included in the project:

## Visualizations

### 1. Total COVID Cases, Deaths, and Vaccinations (Summary Visualization)
This section presents the total number of COVID cases, deaths, and vaccinations globally. These key metrics help understand the overall scope of the pandemic.

- **Total Cases:** 110.4B
- **Total Deaths:** 2.6B
- **Total Vaccinated:** 162.9B

**Key Insight:** This helps grasp the overall scale of the pandemic and vaccination efforts worldwide.

### 2. Aged 65+ vs Aged 70+ by Date (Line Chart)
This Line Chart compares the cases of people aged 65 and older versus those aged 70 and older, showing trends over time. 

**Key Insight:** This allows for analyzing the impact of COVID-19 on different age groups over time.

### 3. Cardiovascular Death Rate by Date (Line Chart)
This chart displays the cardiovascular death rate trend over time, helping visualize its fluctuation across months and years.

**Key Insight:** This chart helps identify periods where cardiovascular death rates spiked or declined, shedding light on how the pandemic influenced other health outcomes.

### 4. Total Cases by Date (Line Chart)
This chart tracks the total number of COVID cases over time (Q1, Q2, Q3, and Q4 of 2020 and 2021). It helps identify trends and changes in case numbers across different periods.

**Key Insight:** This helps monitor the progression of the pandemic and assess how cases changed over time.

## BigQuery SQL Code - 

SELECT
  *
FROM
  `coursera-bigquery-447909.Covid_dataset.covidtable`;

## References
- Link - https://lookerstudio.google.com/reporting/c8d32687-8bbf-4e6d-9f26-863537abad57

## Screenshot
![image](https://github.com/user-attachments/assets/e7112916-c68b-4b79-8d3a-823c7ae4fc9d)


