# POWER-BI
Power BI Assignments

#ASSIGNMENT 1
The Assignment 1 is about data transformation (performing basic data cleaning) using Power Query

##Steps Done-
1.Removed Duplicates. 2.Removed Blank Rows. 3.Removed Columns such as Row ID & Postal code. 4.Changed the headers of the loaded file. 5.Managed Relationships.

#ASSIGNMENT 2
The Assignment 2 is about the detailed sales report of a dataset named "Global Super Store".

##Steps Done-
1.Downloaded the given dataset and loaded it into Power BI.
2.All the preprocessing steps are done by the help of Power Query such as removing the duplicates, removing blank rows,heading correction etc.
3.Managed relationship between the fact table & dimension tables.
4.Segmented the visuals using country, region & market.
5.Calculated the percentage of shipping by shipmode using the DAX formula "ShippingPercentage = DIVIDE(SUM('Orders'[Shipping Cost]),CALCULATE(SUM('Orders'[Shipping Cost]), ALL('Orders'[Ship Mode])))" and visualized it using clustered column chart.
6.Visualized the sales over city, states, region and market by using appropriate charts and visualizations.
7.Created tables for all the visualizations.
8.By using these visualizations, created an interactive sales report to show the stakeholders.
9.Created a video that explains each visualizations.
