# Students' Social Media Addiction Dashboard (Power BI)
## Project Objective
The goal of this project is to analyze the impact of social media on students' academic performance and mental health by studying patterns of usage across different platforms, demographics, and regions. This project also aims to identify which platforms are most popular and how average usage hours may be linked to mental well-being.

# Dataset Used
- <a href="https://github.com/harshadd31/Data-Analysis-Dashboard/blob/main/Students%20Social%20Media%20Addictionn.xlsx">Dataset</a>

# Key Questions / KPIs

- Which social media platforms are most used by students?

- Does high social media usage affect students’ mental health?

- Is there a correlation between social media usage and academic performance?

- What are the regional trends in platform usage (country-wise distribution)?

- How many hours do students spend on social media daily?

- How do age, gender, relationship status, and academic level influence platform preference?

- Dashboard Interaction <a href="https://github.com/harshadd31/Data-Analysis-Dashboard/blob/main/social%20media%20.png">View Dashboard</a>

# Project Process
## 1. Data Collection
Collected responses from students via surveys, including:
Demographic details (Age, Gender, Relationship Status, Academic Level)
Most Used Social Media Platform
Average Daily Usage Hours
Academic Performance Impact (Yes/No)
Mental Health Score
Country of Residence

## 2. Data Preparation (Power Query Editor)
Removed duplicates and cleaned null/missing values.
Renamed columns for clarity and consistency.
Converted appropriate columns into correct data types.
Created calculated columns and measures using DAX:
Count of each platform
Average daily usage
Mental health index per hour range
Academic performance affected (Yes/No)

## 3. Data Modeling
Built relationships between fact and dimension tables.
Developed key metrics using DAX expressions to summarize and filter visuals.
Normalized platform names and standardized scoring mechanisms.

## Dashboard 
<img width="1657" height="958" alt="social media " src="https://github.com/user-attachments/assets/7ea56ddc-88fe-4989-a015-cc5e42572f2d" />

# Dashboard Insights
 ## 1. Most Used Platforms (Donut Chart)
Facebook is the leading platform (37.87%), followed by Instagram (23.11%) and TikTok (22.26%).

LinkedIn and WeChat are the least used.

## 2. Academic Impact (Pie Chart)
66.07% of students said social media affects their academic performance.

Only 33.93% report no impact.

## 3. Usage vs. Mental Health (Area Chart)
Students using social media for 4 to 6 hours/day show a significant fluctuation in mental health scores.

A peak in mental health issues appears around 5 hours/day.

## 4. Platform Preference by Country (Map)
Facebook dominates across various countries.

Instagram and TikTok are more prevalent in select regions (Asia, Europe).

Useful for understanding geographic platform trends.

## 5. Social Media Platform Popularity (Bar Chart)
Facebook has the highest student count, followed by TikTok and WhatsApp.

LinkedIn and WeChat show the least engagement among students.

## 6. Demographic Filters
Slicers for Age, Gender, Relationship Status, and Academic Level allow for segmented insights.

