# -Time-series- Forecasting--Vancouver-airport-energy-usage

Objective
The main goal of this project is to develop a model to forecast monthly energy use for the Vancouver International Airport (YVR).
 
Introduction
Budget planning at YVR requires forecasting the cost of energy to operate the airport. An accurate forecast could help the YVR representatives negotiate more favourable contracts with energy suppliers.
 
Data Available
Data was taken from 14 years of records from the YVR database. This data set includes information on date, energy use, temperature, terminal area, and number of passengers. Data have been aggregated by month into 168 records (14 years with 12 months each).
 
#	Variable	Definition
1	month	Month and year, e.g.: Nov-98
2	energy	Energy use measured in thousands of kilowatt hours (kWh)
3	mean.temp	Mean monthly temperature outside (degrees Celsius)
4	total.area	Total area of all terminals (sq. m.)
5	total.passengers	Total number of passengers in thousands
6	domestic.passengers	Total number of domestic passengers (traveling within Canada) in thousands
7	US.passengers	Total number of passengers traveling between Canada and the US in thousands
8	international.passengers	Total number of passengers traveling between YVR and countries other than Canada/US
 
In this project, you will develop appropriate models, compare the models, and discuss advantages and limitations of each model. You should select the best model and use it to provide monthly forecasts for energy use for the next three years (January 2011 through December 2013).
 
Part B marking rubric
Part B	 	Marks
Introduction and Approach	 	2
EDA	 	4
Potential causes	 	3
Basic methods	 	 
 	Visual comparison	1.25
 	Accuracy measures	1
 	Comparison	1
ETS model	 	 
 	Model	0.25
 	Parameter estimates	0.25
 	Model appropriateness	1.5
 	Model plot	0.75
 	Goodness of fit	1
 	Accuracy measures	1
 	Accuracy of forecasts	1
 	Residual diagnostics	3.5
ARIMA model	 	 
 	Model	0.25
 	Parameter estimates	0.25
 	Model appropriateness	2
 	Model plot	0.75
 	Goodness of fit	1
 	Accuracy measures	1
 	Accuracy of forecasts	1
 	Residual diagnostics	3.5
Comparison of models	 	2
Forecasts	 	1.25
Discussion	 	3
Explanatory model	 	2
Appendix A: ETS	 	1
Appendix B: ARIMA	 	1
Code organized	 	0.5
 	 	 
 	Total	42
