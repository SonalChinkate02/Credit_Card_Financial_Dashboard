# Credit Card Financial Dashboard using Power BI


## Objective :-
To develop a comprehensive credit card dashboard that provides real-time insights into key metrics and trends, enabling stakeholders to monitor and analyze credit card operations effectively.

## Steps :-
### 1.  Import data to SQL database:-
Downloaded the CSV files. Using MySQL workbench, created a new database. I then imported each file into different tables. Then created a successful connection to SQL Server in PowerBI. Now the data is loaded into the PowerBI report.

### 2. Data Cleaning and Preprocessing:-
Once the data is loaded, check for null as well as duplicate values. Then using DAX Queries, created the following data:-
1. AgeGroup:- The column divides the customers into five groups "20-30", "30-40", "40-50", "50-60", and "60+".
2. IncomeGroup:- The column divides the customers into three groups "Low", "Medium" and "High".
3. WeekNum_2:- Gives week number from the column week_start_date.
4. Revenue:- Addition of annual_fees, total_trans_amt and Interest_earned.
5. Current_week_revenue:- measure providing revenue for the current week.
6. Previous_week_revenue:- measure providing revenue for the previous week.

### 3. Dashboard Design:-
Using different charts including Bar charts, Pie charts, Line charts, etc., and powerful PowerBI visuals created an interactive dashboard. The dashboard focuses on the important performance measures residing in data and updating the data in the SQL Database by adding new CSV files to previously created tables. After refreshing the dashboard the changes are visible thus the dashboard is ready for real-time use.

### 4. Project Insights:- 
Week 53 (31st Dec)
1. Revenue increased by 28.8%.
2. Overall revenue is 57M.
3. Total interest is 8M.
4. The total transaction amount is 46M.
5. Male customers are contributing more in revenue  31M, females 26M.
6. Blue and Silver credit cards are contributing to 93% of overall transactions.
7. TX, NY, and CA are contributing to 68%.
8. Overall Activation rate is 57.5%.
9. Overall Delinquent rate is 6.06%.
10. The customers in the age group 40-50 are more likely to contribute in revenue.

## Check out the Dashboard
[Dashboard Link](https://app.powerbi.com/view?r=eyJrIjoiMWUyOWM2MWItNWU1Ny00NjIwLWExOGQtNGIzMTRiMWE2ODNkIiwidCI6IjU1Y2Y5NDAzLTViZjUtNDkwNi04NTQ0LTJhZDhjMzg5MDMyMCJ9)
