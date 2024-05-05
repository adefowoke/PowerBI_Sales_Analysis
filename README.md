<h2 align="center"> PowerBI Sales Analysis Of An Online Global Store</h2>


<div align="center">
<img src="globalstore.jpg"  width="400" height="400" />
</div>
                            
<details>
<summary>Problem Statement</summary>
Global Super Store is an online supergiant store that has worldwide operations. This store takes orders and delivers products across the globe and deals with all the major product categories like furniture, office supplies and technology, and so on.
As a Sales Manager of this store, you want to analyze the sales of the products based on provided historical data, this analysis will help you to plan your inventory and business processes accordingly. Also, to know the product’s and customer’s behavior.
</details>

<details>
<summary>Tasks</summary>
  
1. Load data from the provided data sources (excel workbooks):
 - load both  Date_table and  Super_Store_Sales data into PowerBi by clicking on the 'Get Data' tab and selecting Excel, locate where these data are, and load
   
2. Perform the required data transformations in the Power Query Editor window:
 - When the sales and date data are loaded :
   * promote the first row as the header for each table
   * Ensure the data types for each column are appropriate
 - It is good practice to rename each applied step appropriately for future reference

3. Create the relationships between the loaded tables:
 - Once the transformation is done and loaded, go to the model view to see all the tables.
 - Powerbi might autodetect the relationship between these models, these autodetected relationships between tables might be correct, and other times it might be wrong. This is why it is good practice to always 
   confirm the relationships autodetected by PowerBi.
 - For this project, the relationship autodetected between Returns and People is incorrect, so delete.
 - Drag and drop the 'order date' from the Orders table to the 'Date' in the Date table.
 - Drag and drop the 'Order ID' in the Returns table to the 'Order ID' in the Orders table

5. Create the required measures for key performance indicators like Sales, Profit, and Ratio.

6. Use the visuals as per the provided design to plot dimensions like Category, Year, Region, Market, Sub-category, Manager, and so on. Add key slicers to slice and dice data in the visuals.

7. Train the Q&A data model for the below synonyms: 

- Revenue: Sales 

- Income: Profit

- Income Percentage: Profit Ratio

7. Managers should have restricted data access as per their market allocation by the organization. (Implement RLS)

8.Publish a report in the Power BI Service and share it with other users of the same market role.
</details>

<details>
<summary>Tips for collapsed sections</summary>
### You can add a header
</details>
<details>
<summary>Tips for collapsed sections</summary>
### You can add a header
</details>
<details>
<summary>Tips for collapsed sections</summary>
### You can add a header
</details>
<details>
<summary>Tips for collapsed sections</summary>
### You can add a header
</details>

