README for Project 1 by Yee Hsueh Li
Introduction to and Overview of project:

Data Dictionary:
|Feature|Type|Dataset|Description| 
|rainy_days|int|number-of-rainy-days|numerical number from 1 to 31| 
|total_rainfall|int|total-rainfall-in-a-month-|total rainfall per month in mm|
|rainfall intensity|float|rainfall in 60 min|rainfall amount in 1 hour in mmh-1|

Problem Statement:
Should flights be reduced during heavy rainfall so as to avoid flight delay or flight cancellation as heavy rainfall reduces visibility

Overview of project: 
1.	To answer the problem statement, the days with the threshold rainfall intensity of 10   mmh-1 and above which corresponds to poor visibility needs to be obtained. 
2.	Using the data from monthly total rainfall and monthly number of rainy days from years 2001 to 2021, the month with the highest monthly total rainfall and highest number of rainy days are obtained for each year. 
3.	A summation of the months for highest monthly total rainfall and highest number of rainy days are obtained separately for period 2001 to 2021.
4.	Further data is collected from Meteorological Services Singapore under the daily rainfall in 60 min which gives the maximum rainfall intensity (in mmh-1)

Conclusion and Proposal:
•	November is the month which is likely to have the highest rainfall intensity and therefore lowest visibility hence most likely to result in flight delays and cancellations
•	This is followed by the months of December and January
•	An alert could be set for poor visibility at the 50% or 75% mark of the rainfall intensity using the combined data for the months of January, November and December from year 2014 to 2022
•	Customers-service officers in airline could inform passengers in later flights of a flight delay or flight cancellation if there were going to be one when the alert is activated
•	For the 3 months data, the rainfall intensities are the 19 mmh-1 and 26 mmh-1 at the 50% and 75% mark respectively.

Further research:
If predictions could be made of heavy rain by a month or two or even 6 months ahead, perhaps flights can be reduced for those days where there could be heavy rainfall.

source of data: data.gov.sg, Meteorological Services Singapore
reference:
1)https://www.iata.org/en/iata-repository/publications/economic-reports/airline-industry-economic-performance---october-2021---report/
2)https://www.hindawi.com/journals/amete/2022/5356563/
3)These Asian airlines have the most delays and cancellations now: Travel Weekly Asia (travelweekly-asia.com)
4)Does Rain Cancel Flights? | Sheffield School of Aeronautics
5)Visibility Parameterization For Forecasting Model Applications
  5th International Conference on Fog, Fog Collection and Dew
6)reserchgate.net




