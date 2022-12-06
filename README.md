Hi!

In this repo you can find the data, the EDA process and some of the Machine Learning models we used to try to predict the number of users from a bike rental company in Washington DC.

The initial dataset we were given to calculate a prediction had features like:
    - date
	- season 
	- year 
	- month 
	- holiday
	- weekday 
	- workingday
	- weathersituation : 
	- count of casual users
	- count of registered users
	- count of total rental bikes

The ML models we used were:
* Random Forest
* Gradient Boosting
* XGBoost - which actually gave us the best results

We got relatively good results, but the features that were considered important made us think it could be better...So...

To make more accurate predictions, we needed more data, we searched for it... 
And we found it (on the company's website). Showing the latitude and longitude of the stations, and the duration, time, start and end point of each trip.

For this new data we didn't have time to make more ML predictions, but we analyzed it and extracted new and useful insights for the company! 

You can see the overall project in this Tableau Workbook: https://public.tableau.com/app/profile/chloe7183/viz/GoGreen_2_16661333865190/Next_Steps
Navigate through the tabs from "Intro" to "Next Steps 2" to see the full dashboards.

In this project we used Python and the following libraries:
* Pandas
* Numpy
* Maplotlib
* Seaborn
* Datetime
* Sklearn
* RandomForest
* XGBoost

Done by me & The Outliers Team in Adalab


