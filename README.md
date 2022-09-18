# Extreme Value Theory Estimator

This repository contains data and code that is used to calculate
estimators of the Extreme Value Theory.

The current focus is on the following estimators:

- Hill Estimator
- Pickands Estimator
- Moment Estimator
- Pengs Estimator
- W Estimator

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


## Setup

To take the project from GitHub, you need to install the following:

- git
- python 3.9

To clone the project run the following command in your terminal

```
git clone https://github.com/ericoppermann/Extreme-Value-Theory-Estimator.git
```

This will install the project as a git project on to your local machine. To run the files in the repository run the following command to install necessary packages into your python environment

```
pip install jupyterlab pandas numpy
```

You can then run

```
jupyter lab
```

This will open a virtual machine on a localhost that will be accessed by your webbrowser. Choose a notebook file of your choice. You can run each cell in the notebook by shift and enter.