# AI-Jobs
This project analyzes 15,000 global AI job postings to uncover salary trends, in-demand skills, remote-work patterns, and industry hiring shifts. Cleaned in Excel, transformed with SQL, and integrated with Power BI, it delivers dynamic, real-time insights into the evolving AI job market


🌍 Global AI Job Market Trends & Salary Insights (2025)

This repository presents an end-to-end data analytics project analyzing 15,000 global AI job postings (2024–2025) to uncover trends in salary structures, skill demand, remote-work adoption, industry hiring patterns, and company-level workforce behavior. The project integrates Excel → SQL → Power BI in a dynamic pipeline, enabling automated refresh, real-time insights, and interactive decision-support dashboards.

📌 Project Objectives

Identify global salary trends across AI roles, countries, and industries

Understand the most in-demand technical skills and their salary impact

Analyze remote vs. hybrid vs. onsite workforce shifts

Compare hiring patterns across company sizes and industries

Build a dynamic Power BI dashboard connected to SQL for real-time analytics

📁 Dataset Overview

Source: Kaggle – Global AI Job Market Trend 2025

Records: 15,000 job postings

Fields (29 columns):

Job Title, Salary (USD & local), Experience Level, Employment Type

Required Skills, Education Level

Employer Location, Company Size, Remote Ratio

Industry, Posting Date, Benefits Score, Description Length

and more…

🛠 Tech Stack
Tool	Purpose
Excel	Data cleaning, preprocessing, formatting
SQL	Data modeling, transformation, skill extraction, analytics
Power BI	Dashboards, DAX measures, dynamic SQL connection
DAX	KPIs, calculated measures, dynamic filters
🔄 End-to-End Workflow
1️⃣ Data Cleaning in Excel

Performed initial cleaning to ensure accuracy before loading into SQL.

✔ Removed duplicates using job_id
✔ Standardized country and job title formats
✔ Converted posting & deadline dates to proper formats
✔ Cleaned salary values and ensured numeric consistency
✔ Filled missing fields and validated text columns
✔ Created helper columns (salary groups, remote categories)

Key Excel functions used: TRIM, PROPER, IF, LEN, DATEVALUE, XLOOKUP, TEXT

2️⃣ SQL Data Modeling & Analysis

Once cleaned, the dataset was loaded into SQL for transformation and analytics.

🔹 Major SQL Operations

Salary aggregation (by role, country, industry)

Skill frequency extraction using a recursive numbers table

Experience-level distribution

Remote job percentage by region

Monthly hiring trend analysis

Company-size segmentation

Salary normalization logic
