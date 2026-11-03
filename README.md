copied the data in to new sheet renamed it as solutions
found the total price of all products using the formula =SUM(D2:D35)
found the number of products using the formula =COUNT(E2:E35)
calculated the average price of the product using the formula =AVERAGE(D2:D35)
Determined the minimum price among all products using the formula =MIN(D2:D35)
found the maximum price among all products using the formula =MAX(D2:D35)
Using an IF function, created a new column named Price Range to categorize products with a price greater than or equal to $500 as 'High Price' and others as 'Standard Price', using the formula =IF(D2:D35>=500,"High Price","Standard Price")                           
Calculate the total price for products in the 'Electronics' category using the SUMIF function using the formula =SUMIF(F2:F35,"Electronics",(D2:D35))
Determine the count of products with a price less than $100 using the COUNTIF function using the formula =COUNTIF(D2:D35,"<100")
Created a new column named Day with the first 2 characters of each 'Product ID' using the LEFT function by the formula =LEFT(A2,2)
Created a new column named Country Code by extracting the last 2 characters from the 'Product ID' column using the RIGHT function by the formula =RIGHT(A2,2)
Create a new column named Month by extracting 4th to 6th characters from the 'Product ID' column using the MID function by the formula =MID(A2,4,3)

