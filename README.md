# Sales-Data-Analysis

First step was to clean our data i.e. data preprocessing task. 

Data Preprocessing Tasks include:

1. Drop NaN values from DataFrame
2. Removing rows based on a condition
3. Change the type of columns (to_numeric, to_datetime, astype)

Once the data preprocessing stage is completed, we move to the data exploratory analysis(EDA). In this (EDA), I have explored some high level business questions related to our data:

1.What was the best month for sales? How much was earned that month?
2.What city sold the most product?
3. What time should we display advertisemens to maximize the likelihood of customer’s buying product?
4. What products are most often sold together?
5. What product sold the most? Why do you think it sold the most?
6. Calculate the Total Sales per quarter i.e. for 3 months?
7. Which product was sold most in San Francisco?
8. What are the Least 3 products sold in Texas?
9. Which day have most ordered items and what was top 3 product sold on that day?
10. Which month have most sale for iPhone?
11. What brand of products have higher purchase value?
12. Which state have most product ordered and which is top product orderd and Which product give highest sale?
13. What product(s) is/are sold the most throught out the year?
14. What month of the year is the best to sell laptops?
15. What are the other products sold with headphones?
16. What are the most and least sold products in Portland(ME) and San Francisco(CA)?


To answer these questions I have walked through many different pandas & matplotlib methods. They include:

1. Concatenating multiple csvs together to create a new DataFrame (pd.concat)
2. Adding columns
3. Parsing cells as strings to make new columns (.str)
4. Using the .apply() method
5. Using groupby to perform aggregate analysis
6. Plotting Bar charts, Pie charts and lines graphs to visualize our results
7. Labeling our graphs
