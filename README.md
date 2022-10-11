# Surf's Up

## **Overview**
An investor is considering opening a Surf and Shake shop in Hawaii and wanted us to complete a weather analysis on the weather data set of the island to make decisions on whether to move forward. There would need to be enough rain to keep the island green but not so much to lose out on surfing and ice cream weather.

## **Resources & Tools**
* Data:
* Tools: SQLite, SQLAlchemy, Python, Jupyter Notebook


## **Results** 
We conducted an analysis of the precipitation levels in Oahu, Hawaii to determine whether the surf and ice cream shop's business would be impacted by the weather.

From the hawaii.sqlite database, we filtered the date column in the Measurements table to get the temperatures for the months of June and December. We then converted this to a list, then a DataFrame, and then viewed the summary statistics.

* There were 1700 temperature data points for June and 1517 temperature data points for December.
* June's minimum temperature was 64 degrees while the maximum was 85 degrees. The average temperature was 74.9 degrees.
* December's minimum temperature was 56 degrees while the maximum was 83 degrees. The average temperature was 71.0 degrees.
* Results: 
    * <img width="145" alt="June_Temp" src="https://user-images.githubusercontent.com/110875578/195001399-9f8fb9bc-bc2a-40f2-9d07-4e6db771a3ce.png"> <img width="156" alt="Dec_Temp" src="https://user-images.githubusercontent.com/110875578/195001425-557d934e-a951-4680-a9e0-5bda845b802c.png">

## **Summary**
Provide a high-level summary of the results and two additional queries that you would perform to gather more weather data for June and December.

Using a histogram, we were able to see the frequency distribution of the temperatures throughtout the entire year. It can be seen that temps between 75-80F is measured the most often. The query results are in line with this pattern.

<img width="338" alt="Histogram_Temp" src="https://user-images.githubusercontent.com/110875578/195001469-8241bd2b-9320-4b9e-9fde-5e5f986bd02d.png">

Other queries that would be helpful to make a decision are: 
1) Surf conditions: Surf height & swells are an important part of attracting surfers to our surf and shake shop. Conducting an analysis of how the conditions fare throughout the year would help us determiine whether the business will be successful year round.
2) Hurricane patterns: Since Hawaii is prone to hurricanes and other tropical storms, it would be helpful to analyze the storm patterns throughout the year to determine whether there would be impacts to the business. 
