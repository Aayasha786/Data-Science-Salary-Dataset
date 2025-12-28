Data Science Salaries Analysis

This project analyzes a dataset containing salaries, job roles, experience levels, and company information for data-related positions. The goal is to explore salary patterns, identify top-paying roles, and understand trends based on experience, remote work, and other factors.

Dataset

The dataset is in CSV format.

Contains 3755 rows and 11 columns, including:

work_year: Year of the salary data

experience_level: Experience level of employee (Senior, Medium, Entry, Executive)

employment_type: Full-time, Contract, Freelance, Part-time

job_title: Job designation

salary_in_usd: Salary converted to USD

employee_residence: Country of the employee

remote_ratio: Percentage of remote work

company_location: Country of the company

company_size: Company size (Small, Medium, Large)

Data Cleaning & Preprocessing

Removed unnecessary columns (salary, salary_currency)

Handled missing values by dropping NaNs

Checked for duplicate records

Renamed experience_level codes to descriptive labels

Analysis

Summary statistics: Sum, mean, standard deviation, skewness, and kurtosis for salary_in_usd and work_year

Correlation analysis: Between numeric variables (salary_in_usd, work_year, remote_ratio)

Top job roles: Bar chart of the top 15 job titles

Highest paying jobs: Bar chart of average salaries for all job titles highlighting the highest

Salary by experience: Average salary per experience level visualized with a bar chart

Remote work analysis: Histogram and boxplot of remote_ratio

Technologies Used

Python

Pandas for data manipulation

Matplotlib for data visualization

Usage

Clone the repository:

git clone <repo-url>


Install dependencies:

pip install pandas matplotlib


Load the dataset and run the analysis notebook or script.

Visualizations

Top job roles (bar chart)

Highest paying jobs (bar chart)

Average salary per experience level (bar chart)

Remote work distribution (histogram & boxplot)
