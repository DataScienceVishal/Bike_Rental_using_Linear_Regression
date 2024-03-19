## **Project Description:**

**About Data:**  

day.csv have the following fields:
	
	- instant: record index
	- dteday : date
	- season : season (1:spring, 2:summer, 3:fall, 4:winter)
	- yr : year (0: 2018, 1:2019)
	- mnth : month ( 1 to 12)
	- holiday : weather day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
	- weekday : day of the week
	- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
	+ weathersit : 
		- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
		- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
		- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
		- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
	- temp : temperature in Celsius
	- atemp: feeling temperature in Celsius
	- hum: humidity
	- windspeed: wind speed
	- casual: count of casual users
	- registered: count of registered users
	- cnt: count of total rental bikes including both casual and registered

**Problem Statement:**  
The objective of the project is to predict the total count of rental bikes (including both casual and registered users) based on seasonal variations and weather conditions.

**Solution:**  
Utilizing advanced statistical modeling techniques, including regression analysis, the project seeks to establish predictive models that can accurately estimate the total bike rental count. By leveraging features such as "season" and "weathersit" along with other relevant attributes, the goal is to develop a robust predictive model capable of forecasting bike rental demands under different seasonal and weather conditions.

**Model Performance:**  
The developed predictive model achieved a commendable R-squared score of 71%, indicating a strong correlation between the predicted and actual rental bike counts. This signifies the effectiveness of the model in capturing the variability in bike rental demands based on seasonal and weather factors.

**Libraries Used:**  

**For analysis and numerical functions**
pandas
numpy

**For Visualization and EDA**
matplotlib
seaborn

**Extra**
import warnings

**For modeling and evaluation**
statsmodels
sklearn
