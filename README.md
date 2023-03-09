# Week-6-Introduction-to-spark-independent-project
Project title: Exploratory Data Analysis of Safaricom Stock Prices using PySpark".

This project is an analysis of Safaricom's stock prices over a period of time. The analysis is done using the PySpark library and involves loading the stock data from a CSV file, cleaning and formatting the data, and performing various calculations to gain insights into the trends and patterns in the stock prices.

Dataset
The dataset used for this analysis is a CSV file containing historical data on Safaricom's stock prices. The data includes information such as the date of each trading day, the opening and closing prices of the stock, the highest and lowest prices, and the volume of shares traded.

Analysis
The analysis involves several steps, including:

Loading the data using PySpark and inferring the data types
Cleaning and formatting the data, including converting data types and formatting numbers to two decimal places
Calculating various statistics, such as the mean, max, and min of certain columns, and calculating the correlation between different columns
Aggregating the data by year and month to find trends in the stock prices over time
Some of the specific questions addressed in the analysis include:

What was the day with the peak high in price?
What was the mean of the close column?
What was the max and min of the volume column?
How many days was the close lower than 60 dollars?
What percentage of the time was the high greater than 80 dollars?
What was the Pearson correlation between high and volume?
What was the max high per year?
What was the average close for each calendar month?
Usage
This project can be used as a template for analyzing other stock datasets using PySpark. The code can be easily adapted to work with other datasets by modifying the URLs and column names as needed.

Installation
To run this project, you will need to have PySpark installed on your machine. You can install PySpark using the following command:

!pip install pyspark
You will also need to have a CSV file containing historical stock data. You can download the Safaricom stock data used in this project from the following URL:

Dataset source https://bit.ly/3pmchka

Google colab notebook: https://colab.research.google.com/drive/1pM1g73M0TSZxcuvzjnhENSiOKzIEx-I4?usp=sharing

Credits
This project was created by [Emmanuel Odenyire Anyira]. 
Feel free to use and modify the code as needed.
