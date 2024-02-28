In this project I use Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

I start by cleaning the data. Tasks during this section include:

1. Drop NaN values from DataFrame
   
2. Removing rows based on a condition
   
3. Change the type of columns (to_numeric, to_datetime, astype)
   
Once I have cleaned up the data, I move the data exploration section. In this section I explore 5 high level business questions related to our data:

1. What was the best month for sales? How much was earned that month?

2. What city sold the most product?

3. What time should we display advertisemens to maximize the likelihood of customer’s buying product?

4. What products are most often sold together?

5. What product sold the most? Why do you think it sold the most?

To answer these questions I walk through many different pandas & matplotlib methods. They include:

1. Concatenating multiple csvs together to create a new DataFrame (pd.concat)

2. Adding columns

3. Parsing cells as strings to make new columns (.str)

4. Using the .apply() method

5. Using groupby to perform aggregate analysis

6. Plotting bar charts and lines graphs to visualize our results

7. Labeling our graphs
