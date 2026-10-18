# Power-BI-DAX-Data-Visualization
Data Analytics Project works
Calculated Columns: 

●	Create a Calculated Column for 'Category Type': Add a calculated column in the Order Details table that combines the 'Category' and 'Sub-Category' columns into a single 'Category Type' column : **Power query - Add column - Custom Column - Name of the column - ( Formula )Category & "-" & (Sub Category)**
 
●	Calculate Revenue per Order in Order Details Table: Create a calculated column in the Order Details table to compute the revenue (Amount * Quantity) per order:  **Power query - Add column - Custom Column - Name of the column - ( Formula ) = Amount * Quantity**

●	Create a Calculated Column to Categorize Sales: Add a calculated column named ‘Sales Category’ in the Order Details table that categorizes each order as 'Above Average' or 'Below  Average' based on the Amount value: **Power query - Add column - Custom Column - Name of the column - Formula = if amount > 2000 then "Above Average" else "Below Average"**
 
=====================================================

Calculated Measures: 
●	Calculate Order Count: Define a measure to count the total number of orders in the Order Details table: **Group by > Name the column as > Count > Operation as > Count Row > Ok**
 
●	Calculate Average Profit in Delhi: Create a measure to calculate the average profit for orders placed in Delhi: **Merge Queries > So the profit amount has been moved to List of orders > Group by > Average**
