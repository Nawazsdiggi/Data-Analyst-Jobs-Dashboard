# Data-Analyst-Jobs-Dashboard
Client’s Request / Project Objective
The client wants a dashboard or report that:
Analyzes job trends in Data Analyst positions (using a dataset of 2000+ listings).
Explores:
Salary ranges and patterns.
Locations with best-paying jobs.
Company ratings and ownership types.
Industry / sector demand.
Relationship between company size, sector, and salary.
Predicts or visualizes salary differences based on features like rating, location, company type, etc.
Shows insights that can help job seekers or HR teams understand:
“Where are the best jobs?”
“Which industries or companies pay more?”


Key Steps Completed
Data Collection & Cleaning
Imported job data containing fields like job title, company size, industry, city, salary range, and company type.
Cleaned missing or inconsistent data (e.g., “Unknown” company sizes).
Converted salary values into numerical format for calculations.
Data Modeling
Established relationships between tables (Jobs, Company, and Ratings).
Created calculated columns and DAX measures:
Avg Salary
Total Jobs
Max Salary, Min Salary
Avg Salary by Industry/City/Job
Sum of Rating by Jobs
Dashboard DesignTwo main report pages were created:

                                            🔹  Salary Overview
KPIs: Total Jobs, Max Salary, Min Salary, and Average Salary
Charts:
Avg Salary by Jobs → Compare salary levels across Data Analyst job titles
Avg Salary by City → Visualize salary variation by location
Filters: Job Title, City, and State slicers for dynamic exploration
Avg Salary by Size → Shows how company size impacts salary
Avg Salary by Industry → Compare salaries across industries
Sum of Rating by Jobs → Measures job satisfaction based on company ratings
Jobs Count by Ownership → Visual breakdown by company ownership type (Private, Public, Government, etc.)
Filters: Industry and Rating slicers for easy comparison
Visual Enhancements
Used a purple gradient theme for a clean and modern look.
Applied consistent color coding across charts.
Added navigation buttons for switching between “Salary Overview” and “Company Insights.”
Used tooltips and data labels for better readability.
Insights & Findings
Highest average salaries are found in large companies (5001–10,000+ employees).
Top-paying industries include Drug Manufacturing, Biotechnology, and Information Technology.
Data Analyst roles have the highest count and rating among job categories.
Private companies dominate job postings compared to public or nonprofit organizations.
Certain cities like Pico Rivera and Whittier offer higher salary averages.
Conclusion
This Power BI dashboard provides a comprehensive and interactive view of salary and job market trends for Data Analysts.It helps the client identify top-paying industries, key job roles, and the effect of company size and ownership on compensation.



