# Human Resources Analytics

This repository contains a Human Resources (HR) analytics project conducted using Power BI. The project focuses on analyzing employee data to extract insights on performance, satisfaction, and other HR metrics.

## Introduction
HR analytics, also known as people analytics, involves collecting, analyzing, and reporting HR data to improve business outcomes. By leveraging HR data, organizations can gain insights into employee behavior, performance, and satisfaction, enabling data-driven decision making.

## Goal
The main objective of this project is to analyze employee performance, satisfaction, and turnover at a fictional company for the year 2024. The project also aims to create visual dashboards highlighting key performance indicators (KPIs) and actionable insights.

## Project Overview
The project is structured in the following stages:
1. Data loading
2. Data cleaning
3. Data modeling
4. Data analysis
5. Data visualization

## Dependencies
The tools required for this project are:
- Power BI Desktop

## Technical Skills
Throughout this project, the following skills were applied:
- Data extraction, transformation, and loading (ETL)
- Data modeling using star schema
- Data analysis with DAX functions
- Data visualization and dashboard creation in Power BI

## Dataset
The dataset used in this project includes two Excel files:
- `Hr-analytics-data.xlsx`
- `Hr-employee-data.xlsx`

These files contain employee demographics, performance metrics, satisfaction levels, and other HR-related data.

## Data Loading
Data is imported from the Excel files directly into Power BI for further processing and analysis.

## Data Cleaning
After loading, the data is preprocessed in Power BI using Power Query. This includes:
- Renaming columns
- Adjusting data types
- Removing null and duplicate values

This ensures the dataset is clean and reliable for analysis.

## Data Modeling
A **star schema** is used to model the data for consistent, structured analysis.  
- **Fact table:** Contains quantitative metrics such as performance scores and turnover indicators.  
- **Dimension tables:** Include descriptive attributes such as employee information, education, performance rating, and satisfaction levels.  

Relationships are established between the fact table and dimension tables to enable accurate analysis.

## Data Analysis
The analysis focuses on understanding employee demographics, performance, and attrition trends. Various **DAX measures** were created to perform calculations, aggregations, and comparative analysis for actionable insights.

## Data Visualization
Interactive dashboards are created in Power BI to present the analysis in a visual and user-friendly format. The dashboard contains the following pages:
- Overview
- Demographics
- Attrition
- Employee Performance Analysis

Users can interact with the dashboard to filter and view specific insights.

The original Power BI file, `Hr-analytics.pbix`, is included in this repository for direct download and exploration.

## Insights
The project highlights key findings regarding employee satisfaction, performance trends, and attrition risks. These insights can help HR teams make informed decisions to improve workforce management and business outcomes.
