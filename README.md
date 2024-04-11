# Bike Share data analysis project

## Overview

In this project, I explore and analyze for a fictional company called Divvy. The data is from 2021

## Software used

To complete this project, the following software requirements apply: 

- Python 3, Numpy, Pandas and Plotly installed with Anaconda:
- Jupyter Notebook
- Mac Terminal

# Bike Share Data

The data is structured and tabular. I chose  from April - December 2021 and January - March December. The columns consist of :

- ride_id
- started_at
- ended_at
- start_station_name
- start_station_id
- end_station_name
- end_station_id
- rideable_type
- member_casual
- latitude and longitude columns


## Statistics Computed
- most common bike type
- most common bike type per user type
- count of rides per hour, weekday and month
- avg trip durations
- avg trip duration per user type

## Understanding the Data

Will use pandas to better understand the data. 

Some usefull pandas methods:

- `df.head()`
- `df.columns`
- `df.describe()`
- `df.info()`
- `df['column_name'].value_counts()`
- `df['column_name'].unique()`

Will use plotly to create plots such as line charts and pie charts


## Conclusions

Will find the best recommendations in order to increase member subscribers

Promote campaigs spefifcally for users that use bikes differently that stand out for an oportunity to convert

Such as:

- montly usage
- hourly usage
- bike type usage

