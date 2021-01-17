# surfs_up
Jupyter Notebook, VS Code, and Github are our tools for this Repository.
# Backgroud on project!
### W. Avy likes your analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.
# Challenge requirements
### Using Python, Pandas functions and methods, and SQLAlchemy, you’ll filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June. You’ll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.
### Using Python, Pandas functions and methods, and SQLAlchemy, you’ll filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of December. You’ll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.
# CSVs Produced by the Challenge
[december.csv](december.csv)
![](Data/December.png)
## And
[june.csv](june.csv)
![](Data/June.png)
# Differnce between december and june
1. Over 7 years, there are 1574 precipitations occurred and 1700 temperatures  observed in June, higher than 1405 precipitations and 1517 temperatures  observed in December. The different (1700-1517 = 183) between two observations counts that indicate the data of Dec, 2017 not included in database.

 2. Comparing of precipitation, the mean (0.217) and median (0.03) of December are higher than June’s mean (0.136) and median (0.02), respectively. 

 3. For precipitation derivative indicators, December also had higher Standard Deviations and Maximum precipitation. In December, standard deviation (0.541) is higher than June’s standard deviation (0.336). The minimum of both December and June are zero, and December maximum (6.42) is higher than June (4.43).

 4. Comparing of temperatures, it apparently shows that June’s temperature indicators are higher than December.
# For future analysis I suggest we look for
1.  It would be interesting to see a map of where the measurement stations are located. It's possible that some are nearby good business locations and others are not.
2.  Some data is missing from the prcp column in the database. It would be interesting to extract information on the dates that data is missing to draw a conclusion on why it was not recorded.
3.  Further analysis based on daily, weekly, or yearly time frames is possible. Perhaps to recommend the best weeks of the year to sell ice cream.
