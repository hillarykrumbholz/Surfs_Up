# Surfs Up

## Project Overview
Spend time with tools such as SQLite, SQLAlchemy, and Flask to build knowledge of SQL database structures and querying methods. Will also write and execute Python code in a Jupyter notebook and create graphs using Python.

## Resources
- Data source: hawaii.sqlite
- Software: Visual Studio Code 1.40.2, Flask
- Python libraries: JSON, Pandas, NumPy, Re, psycopg2, SQLAlchemy, SQLite, time, config

## Project Objective
Perform data analysis and exploration on a weather dataset from Oahu to determine of opening a surf shop is worth the time and energy. Want to look at precipitation rates and temperature to see if enough rain is provided to keep the grass green, but not so much that you lose out on ideal surfing and ice cream weather.

## Challenge Overview
Gather data on the seasons of Oahu and determine whether the seasons could affect the surf and ice cream shop business. Specifically, are there certain times of the year when business might be slower, or the type of customer could be different? Your investors want to ensure that there are enough customers between seasons to sustain the business throughout the year.

## Challenge Objective
Determine key statistical data about the month of June and December, and compare the findings. Then make recommendations for further analysis.

## Challenge Summary
Weather information based on comparing the months June and December in Oahu, Hawaii across all years (01/01/2010 – 08/23/2017), and across all nine weather stations.<br/>

![June](https://github.com/hillarykrumbholz/Surfs_Up/blob/master/Images/June.png)<br/>
![December](https://github.com/hillarykrumbholz/Surfs_Up/blob/master/Images/December.png)<br/>

In depth analysis and findings can be found at the botton of the [Climate Analysis Jupyter NB](https://github.com/hillarykrumbholz/Surfs_Up/blob/master/climate_analysis.ipynb) link. 

## Recommendations
1. In order to have more reliable data, I would recommend using an updated database that includes the month of December 2017. This would likely decrease the disparity in number of data points for precipitation and temperature.

2. Additionally, since we are looking to open the Ice Cream Store/Surf Shack in the near future (2020), it would be good to have current precipitation and temperature data. Weather patterns can greatly vary in three years, so in order to make the most informed decision, I would recommend pulling weather data from a weather API, in addition to the stations we are currently looking at. Building on this, we should be looking at more months throughout the years, possibly breaking it up into seasons. This will be able to tell us if there are other months that we should expect greater precipiation and lower temperatures that would possibly hinder our business success.

3. To make things easier for our potentail investors, it would be a good idea to include visualizations, such as a histogram that compares weather between June and December. We could also plot a line graph displaying the temperature throughout the years, to see if we could project weather patterns for future years.
