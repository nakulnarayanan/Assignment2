# Assignment2
Assignment2 for excel
Qn.	Ans.
• Check for missing values in the 'Price' column. How would you handle products with missing price information?	Average value of same type of items. Used =AVERAGEIF(Dataset[Product Name],D2,Dataset[Price ($)])
• If there are products with missing categories, propose a strategy to impute or deal with these missing values effectively.	Given the value Unknown
	
	
• Identify any inconsistent text formats present in the "Product Name" column.	Corrected using Clean, Trim and Capitalize Each Word option
• Identify any typos present in the "Category" column.	Corrected using find and replace option for Electronics
• Use the find and replace function to standardize the text formats in the "Product Name" column and fix any typos or misspellings in the "Category" column.	Corrected the "headphones" text. And Electronics.
	
	
• Identify any duplicate rows within the dataset based on the entirety of each row, and remove them if any.	Used conditional formatting and highilghted the duplicates and removed the duplicate values. Found 3 duplicate values
	
• Split the "Product ID" column into two separate columns for " Manufacturing Date" and "Country Code". Remove unnecessary characters, if any.	Used flashfill option - Cntrl +E
• Merge the "Brand Name" and "Product Name" columns into one column named "Product Brand".	Used & operator and included a space.
	
• Format the data type of the "Price" column to currency format. 	Right click - format - currency - selected English (US) Dollars
• Format the "Manufacturing Date" column to display dates in the "DD-MM-YYYY " format. 	Right click - format - Date - Selected 12-07-2012 format
	
• Apply data bar or color scales conditional formatting in the "Price" column.	Done (Conditional Formatting -> Data Bars)
• Create a custom rule for conditional formatting in the "Category" column to highlight cells where the category is "Electronics."	Go to Conditional formatting -> Select New rule -> Select Format only cells that contains - > Give Cell value equal to Electronics
<img width="826" height="950" alt="image" src="https://github.com/user-attachments/assets/fdacc83b-deba-49ce-8bba-9e24e250bc13" />
