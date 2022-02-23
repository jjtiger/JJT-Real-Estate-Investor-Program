# This JJT Real Estate Investor program was created within a PyViz environment to perform data exploration in the San Francisco real estate market providing a robust interactive visual presentation aiding investors with a clear view of new investment opportunities. 

## Background

A new Real Estate Investment division was requested to provide customers with a broader range of portfolio options. This prototype dashboard provides charts, maps, and interactive visualizations that help customers explore the data and determine if they want to invest in rental properties in San Francisco.


## Files

* [sfo_neighborhoods_census_data.csv](Starter_Code/Data/sfo_neighborhoods_census_data.csv)
* [neighborhoods_coordinates.csv](Starter_Code/Data/neighborhoods_coordinates.csv)
* [Rental Analysis Starter Jupyter Notebook](Starter_Code/rental_analysis.ipynb)
* [Dashboard Starter Jupyter Notebook](Starter_Code/dashboard.ipynb)



### Rental Analysis Dashboard was created in python, in an anaconda pyviz environment. 



#### Housing Units Per Year

A calculation of the number of housing units per year and visualize the results as a bar chart using the Pandas plot function.

Note: By default, the limits auto-scale to the data. However, it is hard to see the difference between the yearly data. In the optional challenge, you can use the min, max, and standard deviation of the data to manually scale the y limits of the plot.

Default Bar Chart



Bar Chart with y-axis limits adjusted




#### Average Housing Costs in San Francisco Per Year

In this section, we determined the average sales price per year and the average gross rent per year to better understand housing costs over time. For example, a customer will want to know if they should expect an increase or decrease in the property value or rent over time so they can determine how long to hold the rental property. One can visualize the average (mean) gross rent and average price per square foot per year and visualize it as a bar chart.

1. Calculate the mean `gross_rent` and `sale_price_sqr_foot` for each year.
2. Visualize the mean `gross_rent` and `sale_price_sqr_foot` for each year as two line charts.

 
#### Average Prices By Neighborhood

In this section, we applied hvplot to create two interactive visualizations of average prices with a dropdown selector for the neighborhood. The first visualization will be a line plot showing the trend of average price per square foot over time for each neighborhood.  The second will be a line plot showing the trend of average monthly rent over time for each neighborhood.



#### Top 10 Most Expensive Neighborhoods

In this section, we figured out which neighborhoods are the most expensive. First, we calculated the mean sale price for each neighborhood and then sort the values to obtain the top 10 most expensive neighborhoods on average. Plot the results as a bar chart.


#### Comparing Cost to Purchase Versus Rental Income

We used a `hvplot` to create an interactive visualization with a dropdown selector for the neighborhood. This visualization will feature a side-by-side comparison of average price per square foot versus average monthly rent by year.


#### Neighborhood Map

In this final section, we read in neighborhood location data and build an interactive map with the average prices per neighborhood. We used a scatter mapbox object from plotly express to create the visualization. Remember,we used a mapbox API key for this.

this required an active account and an access token

####  Cost Analysis - Options

Here we used plotly express to create a Parallel Coordinates plot, Parallel Categories plot, and a Sunburst plot so that investors can interactively filter and explore various factors related to the sales price of the neighborhoods.

Using the provided DataFrame to create the following visualizations:

1.  a Parallel Coordinates Plot.

 

2.  a Parallel Categories Plot.

  

3.  a Sunburst plot to show the most expensive neighborhoods in San Francisco per year.

    **Hint:** You can learn more about sunburst charts in Plotly Express in [this link](https://plotly.com/python/sunburst-charts/).

    
 
---

### Dashboard


