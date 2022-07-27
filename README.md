# Extreme Value Theory Estimator

This repository contains data and code that is used to calculate
estimators of the Extreme Value Theory.

The current focus is on the following estimators:

- Hill Estimator
- Negative Hill Estimator
- Pickands Estimator
- Moment Estimator

For the code checkout:

https://github.com/ericoppermann/Extreme-Value-Theory-Estimator/blob/master/ExtremeValueInvestigation.ipynb

## Data

The data is located in the [data folder](https://github.com/ericoppermann/Extreme-Value-Theory-Estimator/tree/master/data).
There are csv-files that includes the personal bests in 100m Runs from the 
years 2008 to 2020. The data was taken from https://www.worldathletics.org/.

The notebook [DataFiltering.ipynb](https://github.com/ericoppermann/Extreme-Value-Theory-Estimator/blob/master/DataFiltering.ipynb)
prepares and filters the data and calculates the Speed out the personal best times
of each Competitor. Duplicate values are smoothed equally over the interval.

The data folder also contains the Graphs of the calculated estimates as png files.

https://github.com/ericoppermann/Extreme-Value-Theory-Estimator/tree/master/data/graphs

