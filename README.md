# PM2.5
Predicting Air Pollution
Health Impacts
The health impact of air pollution is quite severe. It is estimated that 29% of cardiopulmonary deaths and 40% of lung cancer deaths are attributable to air pollution. Mothers and young children are especially vulnerable. During winter months (when pollution is highest) fetal deaths increase 3.5 times and birth defects are more common.
A recent report from UNICEF found the cost of treating air pollution related illnesses and indirect costs of missed work to be 5.4 billion MNT ($2.2 million USD) per year.

Predicting Air Pollution
Making personal observations is all fine and good, but it doesn’t give a rigorous understanding of air pollution. 
Why PM2.5? 
First, it is one of the most dangerous forms of air pollution. Second, it is the form of pollution tracked by the US State Department at the US Embassy, and they make their data available to the public in a very easy to use format.

Benefits of Predicting
As with any project, the benefits must be clear from the start. Here are what I believe can be some benefits of predicting PM2.5 levels:
1.	Knowing mask/air filtration needs for certain times of day. (Just like we ask ourselves whether we should bring an umbrella if it will rain.)
2.	Knowing whether it will be safe to open the windows today. Often people only look at the pollution levels once a day (if at all). Simply looking out the window isn’t a reliable indicator of pollution.
3.	Knowing if it is a good idea to go outside or to the park, and at what time. Also knowing what part of the city will have cleaner air at a certain time of day can be valuable.
The goal:
The goal of this project is to provide citizens a tool to use in protecting themselves and their families from air pollution.
Dataset Description:
No,
year - Year,
month - Month
day - Day,
hour - hour,
pm2.5 - PM2.5 Concentration,
DEWP - dew point,
TEMP - temperature,
PRES - pressure,
cbwd - wind direction,
Iws - wind speed,
Is - cumulative number of hours of snow,
Ir - cumulative number of hours of rain

Tasks:
1.	Data exploration:
	Visualize PM2.5 by month and make conclusions
	Visualize PM2.5 by hour and make conclusions
	Visualize PM2.5 by wind speed and make conclusions
	Visualize PM2.5 by hour and make conclusions
2.	Clean the dataset (if needed!)
3.	Challenge: Check OLS assumptions: Linearity and No Multicollinearity 
4.	Find features important for the model
5.	Deal with outliers
6.	Perform Linear Regression using sklearn
7.	Evaluate the result
8.	Check different techniques for handling missing data (if exist) and handling outliers


