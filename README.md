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
3️⃣ Power BI Dashboard Development

SQL was dynamically connected to Power BI for automated refresh and real-time insights.
The report contains four fully interactive dashboards:

📊 Dashboard 1: Global Salary Trends

Map: Salary distribution by country
Top-paying AI roles
Experience-level salary gaps
Filters for role, industry, employment type
<img width="1399" height="777" alt="Screenshot 2025-11-30 145230" src="https://github.com/user-attachments/assets/9ab66a44-3c64-4f73-8457-9a21ddb0a906" />

INSIGHTS 
The global average AI salary is $115K, based on 15K job postings across 20 countries.
North America and Western Europe offer the highest AI salaries, as shown by larger map clusters.
AI Specialist, ML Engineer, Head of AI, and AI Research Scientist are the top-paying roles, all above $100K.
Data Analyst ranks lowest in salary compared to other AI roles, reflecting less specialization.
The dashboard’s filters allow comparing salaries by employment type and experience level, enabling deeper role-based insights

🧠 Dashboard 2: Skill Demand

Frequency of top skills (Python, SQL, TensorFlow, Kubernetes, Cloud)
Salary by skill combinations
Education requirement vs hiring volume
Skill–salary correlation matrix

<img width="1397" height="785" alt="Screenshot 2025-11-30 145304" src="https://github.com/user-attachments/assets/7264b524-f90c-4578-91ef-7a2b44a01652" />

INSIGHTS
The average AI salary remains $115K, with Switzerland emerging as the highest-paying country.
Python, SQL, TensorFlow, and Kubernetes are the most in-demand skills, with Python leading at 13K job mentions.
Job distribution is balanced across education levels, with Bachelor and Associate degrees slightly ahead in job count.
Master’s degree holders earn the highest salaries (~$117K), followed closely by Bachelor-level roles.
High-value skills such as Deep Learning, Computer Vision, and NLP show strong salary alignment, highlighting their importance in advanced AI roles

🌐 Dashboard 3: Remote Work Analysis

Remote, Hybrid, Onsite distribution
Hiring trends over posting dates
Jobs by company size
Remote adoption by country

<img width="1391" height="778" alt="Screenshot 2025-11-30 145549" src="https://github.com/user-attachments/assets/7cf45980-308d-47c5-8955-7b77eb344e61" />


INSIGHTS
Remote work distribution is almost equal, with on-site (33.8%), hybrid (33.3%), and fully remote (32.8%) roles showing a balanced hiring trend.
Small, medium, and large companies all offer a similar number of AI jobs, indicating consistent hiring across company sizes.
The average salary remains strong at $115K, regardless of remote category or company size.
Hiring trends fluctuate month to month, with noticeable dips and peaks, showing dynamic AI recruitment activity across 2024–2025.
The presence of filters for industry, company, and year enables deeper insights into how remote work varies across sectors and time periods

🏢 Dashboard 4: Industry & Company Insights
Industry-wise salary averages
Top hiring companies
Benefits score comparison
Salary + Benefits matrix

<img width="1386" height="774" alt="Screenshot 2025-11-30 145645" src="https://github.com/user-attachments/assets/545d95a7-8dc4-495a-bfaa-41b1cc75cb98" />

INSIGHTS
AI hiring is spread across many companies, with firms like TechCorp Inc, Cognitive Computing, and AI Innovations showing the highest job counts.
Consulting leads with the highest average AI salary (~117K), followed by Manufacturing, Media, and Education industries.
Industries such as Automotive and Gaming offer relatively lower salaries compared to technology-driven sectors.
Companies like Algorithmic Solutions, Smart Analytics, and Cognitive Computing provide the best benefits scores, indicating strong employee value propositions.
The dashboard highlights clear differences among industries and companies, helping identify where high-paying roles and strong benefits are most concentrated

📦 Project Deliverables
✔ Cleaned Excel dataset
✔ SQL transformation and analysis scripts
✔ Power BI interactive dashboard (4 pages)
✔ Project documentation and insights

An end-to-end analytics pipeline using Excel, SQL, and Power BI to analyze 15,000 AI job postings. The project reveals global salary trends, in-demand skills, remote-work adoption, and hiring patterns across industries and companies, powered by dynamic SQL–Power BI integration for real-time decision-making




