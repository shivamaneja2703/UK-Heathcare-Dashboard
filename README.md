Healthcare Dashboard
Overview
This project involves the creation of a comprehensive healthcare dashboard using the UK Healthcare dataset in Power BI. The dashboard provides insights into various healthcare metrics, enhancing data-driven decision-making within the healthcare sector.

<img width="668" alt="UK Healthcare Dashboard" src="https://github.com/user-attachments/assets/00b03e6a-54ef-4189-b032-8d1da3648b42">

Steps Followed

1. Data Import and Preparation

Import Dataset: Loaded the UK Healthcare dataset and all associated tables into Power BI.
Data Quality Check: Reviewed the data for errors and null values to ensure data integrity.
Date Formatting: Converted the "Admitted Date" and "Discharged Date" columns from text to date format using the Transform Data option.

2. Data Modeling

Relationships: Examined and established relationships between tables within the Data Model.
Custom Date Table: Created a custom Date table for use in reporting.
DAX Calculation Table: Developed a dedicated table for all necessary DAX calculations.

3. KPI Development

Key Performance Indicators (KPIs): Created KPIs to track critical metrics, including:
Billing Amount
Medication Cost
Treatment Cost
Total Insurance
Room Charges
Out-of-Pocket Expenses
Average Calculations: Calculated the average for each KPI to provide additional insights.

4. Measure Creation

Total Measures: Created measures for total costs, including:
Total Medication Cost
Total Treatment Cost
Total Insurance Covered

Length of Stay: Added a new column, "Length of Stay," by calculating the difference between the Admitted Date and Discharged Date, representing the number of days.
Room Charges Calculation: Developed a measure to calculate the total cost of room charges by multiplying the daily room rate with the Length of Stay using the SUMX iterator function.

Total Billing Amount: Created a measure that sums Total Treatment Cost, Total Medication Cost, and Total Room Charges.
Out-of-Pocket Calculation: Defined a measure to calculate Out-of-Pocket expenses by subtracting Total Insurance Amount from Total Billing Amount.

Average Measures: Created measures to calculate averages for:
Average Insurance Coverage
Average Medication Cost
Average Length of Stay
Average Patient Satisfaction Score
Average Treatment Cost
Total Patients
Average Billing Amount per Visit
Average Room Charges

5. Visualization

Dashboard Design: Designed the dashboard with a light background image created in PowerPoint for a professional appearance.
KPI Cards: Added KPIs using Card visuals and renamed them as per requirements.
Grouping: Organized all measures into folders labeled "Basic Measures" and "Average Measures" within the Data Model.

6. Final Transformations

Visualizations: Transformed the data into meaningful visualizations using the measures and charts created, showcasing total billing amounts, costs by city, procedure, department, diagnosis, and service type.

Conclusion

This healthcare dashboard serves as a powerful tool for visualizing key metrics and insights within the UK healthcare system, supporting informed decision-making and operational efficiency.
