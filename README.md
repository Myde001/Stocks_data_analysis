# Stocks_data_analysis
This is a project exercise where I analyzed the key banking stocks in America

In this data project we will focus on exploratory data analysis of stock prices. Keep in mind, this project is just meant to practice your visualization and pandas skills, it is not meant to be a robust financial analysis or be taken as financial advice.


We'll focus on bank stocks and see how they progressed throughout the financial crisis all the way to early 2016.

# Get the Data
In this section we will learn how to use pandas to directly read data from Google finance using pandas!

Note: You'll need to install pandas-datareader for this to work! Pandas datareader allows you to read stock information directly from the internet Use these links for install guidance (pip install pandas-datareader).


# Data
We need to get data using pandas datareader. We will get stock information for the following banks:

Bank of America, 
CitiGroup, 
Goldman Sachs, 
JPMorgan Chase, 
Morgan Stanley, 
Wells Fargo.

Use datetime to set start and end datetime objects.

** Use [this documentation page](https://pandas-datareader.readthedocs.io/en/latest/remote_data.html) for hints and instructions (it should just be a matter of replacing certain values. Use google finance as a source, for example:**

# Bank of America
BAC = data.DataReader("BAC", 'google', start, end)
