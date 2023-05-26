Power BI project analysis on Myntra:

Objectives:
👉 To understand and analyze the sales performance of Myntra. 

Things i worked on:-
1. Importing data
2. Data cleaning, Data processing, Data Modelling, Data Transformation
3. DAX and Measures
4. Data Visualization using various graphs
5. Reports
6. Final insights

Procedures:

Data gathering & cleaning: 
👉 Imported the data to power BI from excel and performed various activities like Data cleaning, Data processing, Data Modelling, Data Transformation format that can be easily analyzed using power query editor.

Data Processing: 
👉 Created calculated fields using DAX where i have created a table Date_table to get the coulumns according to the requirement .
Date_table = ADDCOLUMNS(CALENDAR(MIN(fact_orders[Date]),MAX(fact_orders[Date])) ,"Month_NAME",FORMAT([DATE],"MMMM"),"Month ID",MONTH([Date]),"year",YEAR([Date]),"Day of Week",FORMAT([Date],"DDDD"),"week id",WEEKDAY([Date]))

Data Modelliing :
👉 Created realationships in the model view between the tables using data Modelling. 

Data Transformation:
👉 Created additional required columns in the tables by doing transformations that are necessary for the visualizations.

Data Analysis using various graphs:
💡 Created Cards to get insight of the total numbers.
💡 Created filters to get selected criteria based on the filters.
💡 Created Maps to show the regions which has highest sales.
💡 Created Bar chart to Products distrubtion.
💡 Created Pie chart to understand Order Status of the customers.

🔍 Insights Drawn:

1. Men were on rank 1 for the year 2021 & it dropped down to rank 2 in 2022 in terms of sales and rank of women for the same has raised from rank 2 to 1.

2. Quarter wise there is no change in the rank for any category or we can say quarterly rank was constant.

3. There is 29% decrease in sales for men category from Qtr-1 to Qtr-2 which is 34% in the case of women, 18% for kids and 27% in beauty products category.

4. Ahmedabad city is placing highest orders in Gujrat, Karnataka is highest order placing city which is in Bengaluru.

5. Cantabil brand is offering least discount for women's jeans.

6. Highest sales by men were made on Friday.
