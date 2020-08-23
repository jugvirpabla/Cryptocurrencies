# Cryptocurrencies

## Resources
- Data Soruce: Crypto_data.csv
- Software: Jupyter Notebooks, Python, Pandas, Standard Scaler, PCA, KMeansm Plotly Express, HvPlot

## Project Summary
In this module, we were asked to help Accountability Accounting help create a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the immense universe of cryptocurrencies and asks you to present a report of what cryptocurrencies are on the trading market and how cryptocurrencies could be grouped toward creating a classification for developing this new investment product.

First off, we preprocessed the data removing any NaNs, and columns that were not needed to create the machine learning model. Then, the data was scaled using PCA, so that call the cryptocurrencies would be weighed the same by the model. 

Next, we clustered the cryptocurrencies to create an elbow curve to help best fit that data. 

Lastly, all the data was visualized with a few charts. The fist was through a 3D scatter plot using Plotly Express, second was a hvplot table with all the current tradable cryptocurrencies, and the last was hvplot scatterplot to contrast the number of available coins versus the total number of mined coins.
