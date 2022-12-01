# Housing Rental Analysis for San Francisco

Used data visualizations, including aggregation, interactive visualizations, and geospatial analysis, to find properties in the San Francisco, CA housing market that are viable investment opportunities.

- Calculate and Plot the Housing Units per Year
- Compare the Average Sale Prices by Neighborhood
- Build an Interactive Neighborhood Map
- Compose a Data Story

### Technologies used

- import `pandas`, `hvplot`, `pathlib`

- Python implementation: CPython
- Python version       : 3.7.15
- IPython version      : 7.31.1

- Compiler    : GCC 11.2.0
- OS          : Linux
- Release     : 5.4.0-1094-azure
- Machine     : x86_64
- Processor   : x86_64
- CPU cores   : 2
- Architecture: 64bit

- hvplot: 0.8.1
- pandas: 1.3.5

### Read in the data
- Use `pd.read_csv` function and Path module, create a data frame. 
- csv file sfo_neighborhoods_census_data.csv 


### Calculate and Plot the Housing Units per Year
- use `groupby` function to group the data by year.
- use `hvplot` function plot the housing_units_by_year.
- use hvplot to plot the `prices_square_foot_by_year` DataFrame as a line plot.

### Compare the Average sale price by neighborhood.
- aggregate the results by the mean of the groups.
- filter out the housing_units column to create a DataFrame that includes only the `sale_price_sqr_foot` and `gross_rent averages` per year.
- use `hvplot` to visualize the `sale_price_sqr_foot` and `gross_rent`. 
- use the `groupby` parameter to create an interactive widget