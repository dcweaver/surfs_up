# Surfs_up

By using the python libraries Pandas and SQLAlchemy, we were able to pull weather data from a SQLite database containing weather data from Hawaii. We queried the database to get the temperatures from June and December in Hawaii. The temperatures were stored as a list, put into a pandas dataframe, and subsequently summary statistics were generated from the dataframes for each month.

## Results
After creating the June dataframe containing all of the temperatures, the summary table below was generated using the describe() function.

![june summary stats](/Resources/june_temps_describe.png)

The same was done for the December temperature dataframe and the below table was generated.

![december summary stats](/Resources/december_temps_describe.png)

### Differences

When comparing the two tables of statistics it jumps out that December had a minumum temperature only 8 degrees lower than that of June. The temperatures in june are consistently higher than that of December, but the average temperature is only 3 degrees higher in June. Lastly, June had a lower standard deviation that December, meaning that the temperatures in June are more consistent than the temperatures in December. 

## Summary 

In conclusion, the temperatures in June and December in Hawaii are much closer than most other places in the world given the climate of the island. The Surf and Ice Cream shop could potentially be a yearround business in this kind of climate, with the summer months getting marginally more business due to the slightly increased temps during that time.

#### Additional Queries

In addition to the queries run on June and December for temperatures, we could also have queried the database to find out about the cloud coverage in June compared to December, or the precipitation amounts during those months as well.