# PyBer_Analysis
#Background
After presentation on module analysis, V. Isualize has and Omar has asked another project analysis utilizing the use of  Python environment  and knowledge of Pandas, they asked to  create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, to create a multiple-line graph that shows the total weekly fares for each city type. A  written report has to be submitted that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## PythonData Environment
 - Anaconda version 1.7.2
 - Conda ver. 4.9.0
 - Jupyter-Notebook version Python 63
 - ipykernal version 7.22
 - Python 3.7.10
 - Pandas 1.2.4
 - Numpy  1.20.1
 - GitBash version 2.28.0.windows.1
 
## Results and Analysis:
After merging the the 2 datasets for city data and ride data  into a data frame (pyber-data_df), we calculate the total rides, total drivers and total amount of fares for each city type. From these numbers, the average fare by ride and average fare per driver for each type  has been calculated and below Pyber Summary data frame was created to show the result.
<img width="302" alt="image" src="https://user-images.githubusercontent.com/92903447/143781705-7049a52a-a62d-45ea-b0ee-f4dfe256dccd.png">

A new dataFrame was created by filtering the dates for 2019-01-01 through 2019-04-28 and  using the resample method in weekly bins below chart was created to plot the resample DataFrame:
<img width="310" alt="PyBer_fare_summary" src="https://user-images.githubusercontent.com/92903447/143780399-7a06393d-496c-4408-8611-a12d44edac00.png">

Per above chart, the three cities are at their peak towards the end of February and begin to drop by March. Moving towards the end of April, both Urban and Suburban remain to be at high peak except for rural . It would be interesting if a determination of whats causing the drop on  on Suburban )for example events or city activities in both cities are causing high and low pattern. 
There are fewer rides and fewer drivers in the rural and suburban areas as compared to the urban areas. The Urban fares are highest compared to the other 2 city types.
Average fares increase as we move away from the urban areas since the rides in suburban and rural areas tend to be more spread out.
Rural cities shows the highest average fare per ride and average fare per driver because the city  has a lesser number of  drivers compared to Urban and Suburban cities.
Rural cities shows  the lowest weekly fares compared to both Suburban and Urban cities.
All three city types start to rise to a peak at the end for February. For the Urban city type, that oscillating peak lasts through April, while the other city types wane in the month of March.The Suburban city type starts to peak again at the end of April, while the Rural city type drops off.

## Summary and Recommendations :

The analysis from gathered dataset shows that there are fewer rides and less drivers in the rural and suburban areas compared to the urban cities. 
The dataset has only the first 5 months of the year, 4 months in fact since the month of May only has 1st week on it. It would be interesting to see how the data looks over the remainder of the year. 
The city events and how spread out the cities or city distances  could be affecting the number of drivers in both suburban and rural, maybe determining what city events  and activity  in the urban and doing the same with the 2 city types will make a similar pattern, it may help increase the revenue on both suburban and rural cities. 
 Moving towards the end of April, both Urban and Suburban remain to be at high peak except for rural . It would be interesting if a determination of whats causing the drop on  on Suburban )for example events or city activities in both cities are causing high and low pattern. 




