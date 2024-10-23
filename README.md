# 📊 Sales Data Analysis Project

In this project, I use **Python Pandas** and **Python Matplotlib** to analyze and answer business questions about **12 months'** worth of sales data. The dataset contains hundreds of thousands of purchases from an electronics store, broken down by month, product type, cost, purchase address, and more. 📈💻

## 🧹 Data Cleaning

The first step of the project is data cleaning. Tasks in this section include:

- Dropping NaN values from the DataFrame to remove incomplete rows. ❌
- Removing rows based on specific conditions, such as faulty entries. ⚠️
- Changing column data types to the appropriate format (using `to_numeric`, `to_datetime`, and `astype`). 🔄

## 🔍 Data Exploration & Business Questions

Once the data is cleaned, I move on to the data exploration section. Here, I explore five high-level business questions:

1. **What was the best month for sales?** How much revenue was earned that month? 📅💰
2. **Which city sold the most products?** 🌆
3. **At what time should advertisements be displayed** to maximize customer purchases? ⏰
4. **Which products are most often sold together?** 🔗
5. **Which product sold the most?** What might be the reason for its popularity? 🏆

## 🛠️ Methods and Tools Used

To answer these business questions, I use various Pandas and Matplotlib methods, including:

- Concatenating multiple CSVs into one DataFrame using `pd.concat`. 📂
- Adding new columns based on calculations or parsing existing data. ➕
- Parsing strings from cells to create new columns using the `.str` accessor. 🔍
- Applying functions to columns using the `.apply()` method for efficient data manipulation. ⚙️
- Grouping data with `groupby` to perform aggregate analysis (e.g., sum, count). 📊
- Visualizing results with bar charts and line graphs for better insights. 📉
- Labeling graphs to enhance clarity and interpretability. 🖊️

This combination of tools allows me to draw actionable insights from the sales data, addressing key business questions for the electronics store. 🚀
