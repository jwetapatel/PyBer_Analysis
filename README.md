# PyBer_Analysis
Using Matplotlib library

# Overview of the analysis:

 In this project we helped Omar to create a summary DataFrame of the ride-sharing data by city type by using Pandas and Matplotlib,
 we conducted the analyses and visualization of the ride-sharing data very similar to Uber. we had two datasets: ride data with location, date and fare for every ride.  The goal was to compare quantity and fares of rides in every city type: urban, suburban and rural; create clear visualization with matplotlib library and provide recommendation to the CEO for addressing any disparities among the city types.

 So we Analyzed foloowing data.
 
 - A ride-sharing summary DataFrame by city type
 - A multiple-line chart of total fares for each city type


# Resources:

Data Sources: city_data.csv, ride_data.csv

Software: Python 3.7.4, Pandas 0.25.2, Matplotlib 3.1.1, Jupyter Notebook

# Results: 

###  A ride-sharing summary DataFrame by city type

- In order to perform the analysis, we merged datasets using left join based on the city column and got a one dataset with all available data. First of all, we created summary dataframe by city type. It has revealed first insight - there are few drivers and rides in rural cities with higher average fares compare to urban cities:

- There are 13 times more rides in urban cities compare to rural cities (1,625 vs 125 rides)
- The average fare per ride is 1.4 times less and average fare per driver is 3.4 times less in urban cities compare to rural cities ($24.53 vs $34.62 and $16.57 vs $55.49)
- The total fares in urban cities is 9 times higher than in rural cities and 2 times higher than suburban cities. ($39,854.38 vs $4,327.93) 

![ride sharing data](https://user-images.githubusercontent.com/96400887/168848418-1c359844-5e45-4566-a400-05d0ace1d45c.png)

### A multiple-line chart of total fares for each city type

- The multiple-line chart "Total Fare by City Type" further supports the PyBer Summary DataFrame by providing trends of total fares in rural, suburban, and urban cities between January 2019 and April 2019. 
 
- The yellow trend shows how fares in urban cities totaled from around $1,600 to $2,300 from beginning to end during this five-month period. In contrast, the blue trend shows how fares in rural cities totaled around $300 from beginning to end during the same time period. The orange trend shows how the total fares in suruban cities fall in between urban and rural cities

- Around $700 to $1,300 from beginning to end during this time. The chart further demonstrates similar peak times in all these types of cities. One noteworthy peak in total fares among urban, suburban, and rural cities occurred sometime at the end of February 2019.

![Line chart of ride sharing data](https://user-images.githubusercontent.com/96400887/168849944-d21a2d97-74d3-413f-9f5f-e016cf32c7c9.png)

# Summary:

- The datashows that urban cities do significantly more business than suburban or rural cities based on the the 4-10x number of rides and 5-30x number of drivers in urban cities compared to rural and suburban ones.
- It's also interesting to note that the average fares are the lowest for drivers and ride in urban cities. This shows that trips are shorter/cost less in urban areas and that due to the high number of drivers, each employee makes less on average in urban cities compared to rural or suburban ones.
- The graph shows a very consistent trend across the different city types. Urban cities consistently bring in the most money, followed by suburban ones, and finally rural cities. The plots vaguely mirror eachother with all three dropping their total fares in March before peaking mid-late February.









