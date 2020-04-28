# Bay-Wheels-Bike-Udacity-Project
## by (Sanchi Lunawat)

# Dataset
This Analysis was done around data from 2020 (January - March) and pulled off of the public lyft link. Some of the steps taken to clean this dataset involved dropping unwanted columns, converting rental time into minutes, calculating distance based on latitude & longitutde.  

# Dependencies
This project required pandas, numpy, matplotlib, seaborn, and datetime 

# Project Steps
*Load & Clean datasets pulled from website
*Develop Key Questions to answer from datset
*Visualize data for clean understanding

# Questions addressed in project (using 2020, Jan-March data)
* Number of bikes rented each month 
* Duration of bike rides depending on if rider was Customer or Subscriber
* Duration of bike rides by month
* Distance traveled in correlation with duration of bike rides

# Sources for investigation
Data from: https://www.lyft.com/bikes/bay-wheels/system-data
Lat & Long python code: https://kanoki.org/2019/12/27/how-to-calculate-distance-in-python-and-pandas-using-scipy-spatial-and-distance-functions/ 
Seaborn plots: https://seaborn.pydata.org/

## Summary of Findings

> Overall, data shows that bike rides peaked in Feburary, and dipped quit signficantly in March. This dip could have been caused by Covid-19 as many people started traveling less and quarantined themselves. Additinaly, at any month in the dataset, there were a higher number of bike rentals from customers than users. Also by month, the average time of bike rental was higher in Feb than any other month as the scatterplot will illustrate.  

## Key Insights for Presentation
Key insight: By looking at latitude and longitude I was able to approximate how far riders when during each ride. Interestingly enough, there is not a signficant correlation between the amount of time bikes were rented for and the distance traveled. There are a probably a lot of riders who leasiurly take ride bikes and have many stops, resulting in high time rented but low distanced traveled.
