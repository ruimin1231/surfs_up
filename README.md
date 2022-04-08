# Surfs_Up
---
### _Analyzing weather data on Python from an SQLite Database using SQLAlchemy and a Flask App_

# Overview
---
This project consisted on analyzing weather data from Oahu, Hawaii to support a Surf and Ice-cream shop investment proposal. The analysis consisted on determining whether the seasons could affect the surf and ice-cream business. The final product was a full report and a flask application that read the data from a SQLite Database for other users to access it.

# Resources
---
* Data resources:
 - hawaii.sqlite
 
 ### Software used:

* Python
* SQLAlchemy
* SQLite
* Flask

## Results

Statistical results of the precipitation and temperature of the two most active and important months across the years as follows:

[June & December Png files](screenshots)

1. As it can be seen, the average temperature for both June and December are considered good weather suitable for ice-cream (71°F and 74.0°F).

2. None of the two seasons of the year show to have considerably high average precipitation. The precipitation distribution for both June and December happens to be skewed to the right meaning that it is not normally raining. 1st Quartile and median have 0mm, and the 3rd Quartile has 0.1mm which is minimum precipitation.

3. It must be taken into consideration that the month of december happens to have a max precipitation of 6.4mm which is considered heavy rain. On the other hand, the max precipitation for June happens to be 4.4mm which is considered medium-high. Overall, the distribution shows that precipitation might not be enough reason to close our shop out-of-business due to weather conditions.

4. Taking all this into account, June happens to be the most profitable time of the year as the distribution of the weather is more suitable for surfing and ice-cream sales.

## Summary
___
The results were found by querying the SQLite database from the Jupyter notebook to then use the describe() function to get the statistical analysis.

For more detail on the Python script and libraries used refer to the [Surfs_up](SurfsUp_Challenge.ipynb)
