# pandas-challenge-1
Module 4 - Pandas

# Part 1: Explore the Data
## Import the data and use Pandas to understand dataset.

View the column names in the data

Use the describe function to gather some basic statistics

Familiarize yourself with the data.

Check what three item categories had the most entries

Store the client ids of those top 5 clients in a list

Check how many units (the qty column)  the client with the most entries order order


# Part 2: Transform the Data
## Work with the database to filter on some key data

Create a column that calculates the subtotal for each line using the unit_price and the qty

Create a column for shipping price.vAssume a shipping price of $7 per pound for orders over 50 pounds and $10 per pound for items 50 pounds or under

Create a column for the total price using the subtotal and the shipping price along with a sales tax of 9.25%

Create a column for the cost of each line using unit cost, qty, and shipping price 

Create a column for the profit of each line using line cost and line price


# Part 23: Confirm your work
## You have email receipts showing that the total prices for 3 orders. Confirm that your calculations match the receipts. Remember, each order has multiple lines

Check your totals with the file for Order ID 2742071, 2173913, 6128929 


# Part 4: Summarize and Analyze
## Use the new columns with confirmed values to find the following information

How much did each of the top 5 clients by quantity spend? 

Create a summary DataFrame showing the totals for the for the top 5 clients with the following information: total units purchased, total shipping price,total revenue, and total profit. Sort by total profit.

Format the data and rename the columns to names suitable for presentation -  currency should be in millions of dollars

Sort the updated data by "Total Profit" form highest to lowest