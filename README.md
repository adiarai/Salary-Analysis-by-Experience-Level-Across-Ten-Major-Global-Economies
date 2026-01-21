<img width="727" height="453" alt="ad2" src="https://github.com/user-attachments/assets/cf41b538-2e32-4510-bc56-b2c0729a28f0" />
<img width="679" height="656" alt="ad 1" src="https://github.com/user-attachments/assets/0d4b9748-5e52-4a26-8e97-98740ea00569" />
📌 Project Overview

This project analyzes data science salaries based on experience level and company size using Python.
The goal is to understand how salaries change depending on seniority and organization size, and to present insights using statistics and visualizations.

🗂 Dataset

Source: data_science_salaries.csv

Total records: 245

Key features:

experience_level (EN, MI, SE, EX)

company_size (S, M, L)

salary_in_usd

job_title, employment_type, remote_ratio, etc.

🛠 Tools & Libraries

Python

Pandas – data loading, cleaning, grouping, aggregation

Matplotlib – boxplots and bar charts

🔍 Data Preparation & Exploration

Loaded the dataset using Pandas

Checked:

Data types

Missing values (✔ no missing values)

Unique values for experience level and company size

Converted and analyzed salary data in USD for consistency

📈 Analysis Performed
1️⃣ Salary by Experience Level

Grouped salaries by experience level and calculated:

Mean

Median

Minimum and maximum

Standard deviation

Key insight:

Executive-level roles earn significantly higher salaries

Entry-level roles have the lowest salary range

2️⃣ Salary by Company Size

Analyzed salaries across:

Small (S)

Medium (M)

Large (L) companies

Key insight:

Large companies generally offer higher average salaries

Small companies show higher variability

3️⃣ Combined Analysis (Experience × Company Size)

Grouped salaries by both experience level and company size to understand combined effects.

Key insight:

Senior and executive roles in large companies receive the highest compensation

Entry-level salaries vary strongly by company size

📊 Visualizations

Boxplots

Salary distribution by company size

Salary distribution by experience level

Bar Chart

Mean salary comparison across company size and experience level

These visualizations help clearly communicate salary trends and outliers.

✅ Key Findings

Salary increases strongly with experience level

Large companies tend to pay more across all levels

Executive salaries show high variance due to different roles and regions

Entry-level roles are most sensitive to company size

🎯 Conclusion

This project demonstrates how Python and Pandas can be used to:

Clean and explore real-world data

Perform statistical analysis

Generate insights for business and career decisions

Visualize patterns clearly for stakeholders

🚀 Skills Demonstrated

Data analysis with Pandas

Groupby & aggregation

Exploratory Data Analysis (EDA)

Data visualization with Matplotlib

Business-focused interpretation of results
