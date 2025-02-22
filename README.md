# POWER-BI
Power BI Assignments

ASSIGNMENT 1
The Assignment 1 is about data transformation (performing basic data cleaning) using Power Query

Steps Done
1.Removed Duplicates. 2.Removed Blank Rows. 3.Removed Columns such as Row ID & Postal code. 4.Changed the headers of the loaded file. 5.Managed Relationships.

ASSIGNMENT 2
The Assignment 2 is about the detailed sales report of a dataset named "Global Super Store".

Steps Done
Downloaded the given dataset and loaded it into Power BI.
All the preprocessing steps are done by the help of Power Query such as removing the duplicates, removing blank rows,heading correction etc.
Managed relationship between the fact table & dimension tables.
Segmented the visuals using country, region & market.
Calculated the percentage of shipping by shipmode using the DAX formula "ShippingPercentage = DIVIDE(SUM('Orders'[Shipping Cost]),CALCULATE(SUM('Orders'[Shipping Cost]), ALL('Orders'[Ship Mode])))" and visualized it using clustered column chart.
Visualized the sales over city, states, region and market by using appropriate charts and visualizations.
Created tables for all the visualizations.
By using these visualizations, created an interactive sales report to show the stakeholders.
Created a video that explains each visualizations.
