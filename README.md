# Communicate_Data_Finding

## Dataset used 
[FordGoBike](https://www.lyft.com/bikes/bay-wheels/system-data)

## Introduction
This project is divided into two major parts. In the first part, we will conduct an exploratory data analysis on a  [FordGoBike](https://www.lyft.com/bikes/bay-wheels/system-data) dataset. We have used Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships. This part of the project is our opportunity to ask questions of the data and make our own discoveries. Some of the exploration can lead to dead ends, and that it can take multiple steps to dig down to what we’re truly looking for. 

In the second part, we have taken our main findings from our exploration and convey them to others through an explanatory analysis. To this end, we have created a slide deck that leverages polished, explanatory visualizations to communicate our results. 

## Summary of Exploration Data Analysis
In this exploratory data analysis, we have used trip data collected from June 2017 through December 2019. Because of memory limitation, data is kept in three different files corresponding to three years 2017, 2018 and 2019.

* 2017 data file has 5,19,700 trips information. It has 13 features.
* 2018 data file has 18,63,721 trips information. It has 14 features.
* 2019 data file has 25,06,983 trip information. It has 15 features.

Interesting observations:
* Most of the trip data have short distance and short duration.
* User Type feature seems to be the most useful categorical feature to get more insight.
* Duration, distance, start time (day, month, hour) seem most useful features in explanatory analysis later.
* Trip data are anonymized. So all user personal information (e.g. age, gender etc) are removed in this data.

For more details and code, check the `Exploratory_Data_Analysis.ipynb` notebook and corresponding report.

## Summary of Explanatory Data Analysis
There are two types of clients using the system: Subscribers and Customers. Subscribers are primarily daily commuters, having short trips to and from work, who rent a bike on weekdays at 8-9am and 5-6pm. Customers are usually tourists or occasional riders who use the system mainly on weekends to explore the Bay Area. In 2019, some commuter subscribers seem to withdraw their membership and tend to use the bike service as non-member customers as indicated in customer vs subscriber proportion and rush hour patterns by user type and start day graphs. 

For more details and code, check the `Explanatory_Data_Analysis.ipynb` notebook and corresponding report.

## References
* [Ford GoBike System Data](https://www.lyft.com/bikes/bay-wheels/system-data)
* [Plot two histograms on single chart with matplotlib](https://stackoverflow.com/questions/6871201/plot-two-histograms-on-single-chart-with-matplotlib)
* [Calculate distance between Lat/long points](https://www.movable-type.co.uk/scripts/latlong.html)
* [Pandas legend for scatter matrix](https://stackoverflow.com/questions/43801637/pandas-legend-for-scatter-matrix)
* [Pie Chart Demo](https://matplotlib.org/3.2.1/gallery/pie_and_polar_charts/pie_demo2.html#sphx-glr-gallery-pie-and-polar-charts-pie-demo2-py)
* [Slide Deck Tutorial](https://github.com/chelseymarie6/Communicate-Data-Findings/blob/master/Communicate_Data_Slide_Deck.ipynb)
