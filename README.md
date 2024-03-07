# Mercadolibre_timeseries_module11_challenge

Objective:  Create jupyter notebook that, using Python coding through the Google Collab workspace, to analyze and visualize a time series study of MercadoLibre’s search and stock price trends.
The file containing the Python code is named forecasting_net_prophet.ipynb

## Find Unusual Patterns in Hourly Google Search Traffic
After installing and importing the required libraries and dependencies, we import the files to create the data frame we will use for our analysis of the search trends. The code checks for the data types and then slices the data to show and visualize only the data for a particular month.  Next, the code calculates some search trend data to determine if the traffic of the particular month was higher than in previous months due to some financial results announcements.

The code then searches for seasonality on the trends.  The code uses the groupby approach to see trends for the day of the week and creates a heatmap to help visualize and interpret any trends.  The code then does a subsequent timeseries analysis for a week range to visualize and interpret any trends.

## Search Traffic and Stock Price trends
In order to create the correct data frame to do the analysis, the code concatenates the stock price data and the search data.  After the new data frame is established, the code slices the data to focus in a 6-month period in 2020.  The code then plots the data to help determine if the current events during those months appear to relate to the stock/search trends.
The code then adds columns to the data frame to perform some additional statistical metrics to evaluate the data further on its risk and performance.  The correlation between these statistical variables is compared to determine if a predictable relationship exists between the search traffic and stock volatility or the search traffic and the stock price returns.

## Create a  time series model with Prophet

The code first modifies the existing data into a data frame that can be applied to a Prophet model.  The index is reset and columns are renamed with all null values dropped.  The code then fits the data frame to the time series model, creates a future data frame and a forecast data frame.  The results of the model are visualized to help determine the near term forecast of MercadoLibre.  Finally, the model components are also visualized to determine any trends or seasonality by hour, day or month.

### Resources
Berkeley Extension Fintech Bootcamp Class Materials


