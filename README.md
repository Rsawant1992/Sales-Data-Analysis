# Sales-Data-Analysis

First step was to clean our data i.e. data preprocessing task. 

Data Preprocessing Tasks include:

1. Drop NaN values from DataFrame
2. Removing rows based on a condition
3. Change the type of columns (to_numeric, to_datetime, astype)

Once the data preprocessing stage is completed, we move to the data exploratory analysis(EDA). In this (EDA), I have explored some high level business questions related to our data:

What was the best month for sales? How much was earned that month?
What city sold the most product?
What time should we display advertisemens to maximize the likelihood of customer’s buying product?
What products are most often sold together?
What product sold the most? Why do you think it sold the most?
Calculate the Total Sales per quarter i.e. for 3 months?
Which product was sold most in San Francisco?
What are the Least 3 products sold in Texas?
Which day have most ordered items and what was top 3 product sold on that day?
Which month have most sale for iPhone?
What brand of products have higher purchase value?
Which state have most product ordered and which is top product orderd and Which product give highest sale?
What product(s) is/are sold the most throught out the year?
What month of the year is the best to sell laptops?
What are the other products sold with headphones?
What are the most and least sold products in Portland(ME) and San Francisco(CA)?


To answer these questions I have walked through many different pandas & matplotlib methods. They include:

Concatenating multiple csvs together to create a new DataFrame (pd.concat)
Adding columns
Parsing cells as strings to make new columns (.str)
Using the .apply() method
Using groupby to perform aggregate analysis
Plotting Bar charts, Pie charts and lines graphs to visualize our results
Labeling our graphs
