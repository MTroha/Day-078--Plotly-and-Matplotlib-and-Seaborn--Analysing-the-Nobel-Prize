# Day-078--Plotly-and-Matplotlib-and-Seaborn--Analysing-the-Nobel-Prize
Pandas, Matplotlib, Plotly and Seaborn

Pandas (pd):
- Basic Data Cleaning --> preparing the data for analyzing
  - .describe() --> descriptive statistics of a DataFrame
  - drop NaN values
  - convert object and string to numbers --> converting pd.Series '1/2' (str) into 0.5 (float)
  - rolling average to smooth out time-series and show the trend
  - .value_counts(), .groupby(), .sort_values(), .agg()

Plotly (px):
- Basic plots
  - pie and donut chart
  - line and bar chart
- .choropleth() --> display data on a map
- .sunburst() --> create sunburst chart --> SO COOL !!!

Seaborn (sns):
- .histplot() --> create a histogram
- .regplot() --> create a regression plot('scatter + trendline')
  - .regplot(lowess=True) --> more accurate trendline
- .boxplot() --> create box chart (similar to px.box())
- .lmplot() --> create multiple separate plots one under the other 
