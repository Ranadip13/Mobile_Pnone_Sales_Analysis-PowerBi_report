# Mobile Sales Analysis PowerBi Rreport
This Mobile Phone Sales report is based on the FP20 Analysis Challenge. The aim is to explore business patterns in the sales data and summarize the findings into meaningful sales insights.

### Data Exploration and Validation:
* Imported the CSV file containing the sales data into Power BI.
* In the Power Query section, checked the columns for errors and validated their data types against the column values.
* Identified and removed 1,499 duplicate values.
* Proceeded to create the dashboard.

### DAX Functions: 
To better address some business questions, calculated columns and measures were added. The SUMX function was used to create measures for Total Sales, Total Cost, and Total Profit. Additionally, the CALCULATE and PREVIOUSYEAR functions were used to obtain previous year sales and profits. For year-to-date (YTD) and quarter-to-date (QTD) sales, the DATESYTD and DATESQTD functions were utilized. Furthermore, the STARTOFMONTH and STARTOFYEAR functions were used to create new columns for the start of each month and the start of each year.

### REPORT - BUSINESS SOLUTION:
This report consists of two pages: the first provides an overview, and the second focuses on sales analysis.

Page 1: Overview
* Cards: Display total sales, profit, number of mobiles sold, etc.
* Multi-Row Cards: Highlight sales by brand, country, distributor, and operator.
* Matrix: Show overall sales by country and brand in tabular form.
* Bar Charts: Graphically present the sales performance of brands, distributors, and operators.
* Bookmarks: Used to combine these charts, allowing users to view them based on their interests.

Page 2: Sales Analysis
* Slicers: Enable filtering by country, date, and brand.
* KPI: Show the performance of sales between the current year and the previous year.
* Field Parameters: Total sales, total profit, and total quantity sold measures are converted into field parameters.
* Line Chart: Created using field parameters to show trends in sales, profit, and the number of mobiles sold over time.
* Page Navigation: Enhances the report's interactivity, providing a better user experience.

### Insights:
* With the highest sales and profit, Apple emerged as the most profitable brand in the industry.
* Despite having the lowest sales, Huawei achieved the highest profit margin at 61%, nearly double that of Apple. Huawei should focus on marketing to boost sales.
* With the highest sales, Colombia has become the best market for mobile companies.
* Tottus achieved the highest sales and became the top profit-generating distributor.
* Saga Falabella and Ripley recorded the lowest performance. They should consider focusing on distributing high-demand phones like those from Apple, LG, and Samsung.
* Sales declined from October 2019 to December 2020, likely due to the COVID-19 pandemic. However, there was an upward trend in sales during 2021. 
* In 2021, LG and Samsung significantly increased their sales, while Apple's sales did not grow despite their premium segment phones.

Project Link: https://app.powerbi.com/groups/me/reports/544d5993-f70c-4c2b-b1e0-8cd704bef572/a97bf7bb91a7e03ce41e?experience=power-bi
