# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
Analyze restaurant / bar listings near bike stations in Toronto

## Process
Connect to CityBikes API
Query and parse relevant results
Connect to Foursquare API
Query and parse relevant results
Connect to Yelp API
Query and parse relevant results
Connect dataframes using SQLite
Build regression model

## Results
Foursquare provided more unique listings in the queried area but Yelp provided more comprehensive information for analysis, including ratings and pricing data. In all, Yelp was the more useful data source.

## Challenges 
API calls took a long time to set up and format properly to run on a list of locations. Properly parsing the hierarchical data and merging the results of searches also proved time intensive.

## Future Goals
Generating a more specific/useful data question / use case would have allowed me to limit the number of API calls made and the number of results they returned. It also would have permitted me to identify a more informative target for a regression model.
