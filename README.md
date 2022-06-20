# Time Series Forecast

This program analyzes an e-commerce site's financial and user data to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock. The program will depict seasonality of the data, evaluate the stock prices in correlation to user searches, and forecast and predict hourly search traffic. The program will also visualize future revenues forecasted.

----

## Technologies
This application is written in Jupyter Lab Notebook in the Python programming language. It was edited in Google Colab. The Python libraries, tools, and modules used in this application are Pandas, hvPlot, Prophet, Holoviews, PyStan, Matplotlib, and datetime.

[Pandas](https://pandas.pydata.org/docs/index.html), [hvPlot](https://hvplot.holoviz.org/), [Prophet](https://facebook.github.io/prophet/), [HoloViews](https://holoviews.org/), [PyStan](https://pystan.readthedocs.io/en/latest/), [Matplotlib](https://matplotlib.org/), [datetime](https://docs.python.org/3/library/datetime.html)

----

## Installation Guide
This program uses the Pandas library. If the user is not already running an environment that includes Pandas, then they will need to intall the library. Instructions shown in the installation guide --> [Pandas Installation Guide](https://pandas.pydata.org/docs/getting_started/install.html)

The user must install the required libraries. If running the program in Google Colab, run the following in a cell that preceeds the rest of the code:

    !pip install pystan
    !pip install fbprophet
    !pip install hvplot
    !pip install holoviews

This will remotely install the above libraries and allow the user to successfully run the program.

----

## Usage
For the program to run correctly, the user must make sure that all libraries and modules are correctly imported in the beginning of the code. This looks like:

    import pandas as pd
    import holoviews as hv
    from fbprophet import Prophet
    import hvplot.pandas
    import datetime as dt
    %matplotlib inline


**The program is comprised of 5 parts:**

1. Find Unusual Patterns in Hourly Google Search Traffic

2. Mine the Search Traffic Data for Seasonality

3. Relate the Search Traffic to Stock Price Patterns

4. Create a Time Series Model with Prophet

5. Forecast Revenue by Using Time Series Models


----

## Contributors

Arlie Jones

[E-mail](arliejones98@gmail.com)  |  [LinkedIn](https://www.linkedin.com/in/arlie-jones-020092159/)

----

## License

None
