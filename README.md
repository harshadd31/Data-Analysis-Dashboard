# Students' Social Media Addiction Dashboard (Power BI)
## Project Objective
The goal of this project is to analyze the impact of social media on students' academic performance and mental health by studying patterns of usage across different platforms, demographics, and regions. This project also aims to identify which platforms are most popular and how average usage hours may be linked to mental well-being.

## Dataset Used
- <a href="https://github.com/harshadd31/Data-Analysis-Dashboard/blob/main/Students%20Social%20Media%20Addictionn.xlsx">Dataset</a>

## Key Questions / KPIs

- Which social media platforms are most used by students?

- Does high social media usage affect students’ mental health?

- Is there a correlation between social media usage and academic performance?

- What are the regional trends in platform usage (country-wise distribution)?

- How many hours do students spend on social media daily?

- How do age, gender, relationship status, and academic level influence platform preference?

- Dashboard Interaction <a href="https://github.com/harshadd31/Data-Analysis-Dashboard/blob/main/social%20media%20.png">View Dashboard</a>

## Project Process
# 1. Data Collection
Collected responses from students via surveys, including:
Demographic details (Age, Gender, Relationship Status, Academic Level)
Most Used Social Media Platform
Average Daily Usage Hours
Academic Performance Impact (Yes/No)
Mental Health Score
Country of Residence

# 2. Data Preparation (Power Query Editor)
Removed duplicates and cleaned null/missing values.
Renamed columns for clarity and consistency.
Converted appropriate columns into correct data types.
Created calculated columns and measures using DAX:
Count of each platform
Average daily usage
Mental health index per hour range
Academic performance affected (Yes/No)

# 3. Data Modeling
Built relationships between fact and dimension tables.
Developed key metrics using DAX expressions to summarize and filter visuals.
Normalized platform names and standardized scoring mechanisms.
