## Abstract

### Purpose
To unlock sales insights that are not visible before for sales team for decision support & automate them to reduced manual time spent in data gathering.

### Stake Holders
- Sales Director
- Marketing Team
- Customer Service Team
- Data & Analytics Team
- IT

### End Result
An automated dashboard providing quick & latest insights in order to support data driven decision making.

### Success Criteria
- Dashboard(s) uncovering sales order insights with latest data available.
- Sales team able to take better decisions & prove 10% cost savings of total spend.
- Sales Analysts stop data gathering manually in order to save 20% of their business time and reinvest it value added activity.

## Methodology
In this project, I leveraged Power BI to establish a connection with a MySQL database. By configuring this connection, I was able to import data and tables from MySQL directly into the Power BI environment. This integration allowed for real-time data extraction, ensuring that the visualizations and reports in Power BI were based on the most current data available in the MySQL database. The seamless data flow between MySQL and Power BI significantly enhanced the efficiency and accuracy of the data analysis and reporting process.

The following diagram presents the data model, highlighting the relationships between various tables. It visually represents how the tables are interconnected, facilitating a better understanding of the data structure.

![image](https://github.com/sharmiladulmi/Sales-Dataset-using-Power-BI/assets/75578997/15f2f84a-0460-43fe-9e31-838854d5c8d5)

Power BI includes a table mode where we perform data transformation, data cleaning, data wrangling, and data merging tasks. In this project, we have carried out the following actions:

- Removed null values from the sales market table.
- Removed 0 and -1 values from the sales amount column in the sales transaction table.
- Added a new column named 'norm_sales_transactions,' which normalizes the sales transactions to the Indian currency format.
- Removed duplicate values 'INR' and 'USD' from the currency column in the sales transactions table.
- Changed the date format in the 'cy_date' column in the date table.



![Screenshot 2024-05-27 152656](https://github.com/sharmiladulmi/Sales-Dataset-using-Power-BI/assets/75578997/ce08d7ee-ae95-4687-bf8b-d17891982e51)
