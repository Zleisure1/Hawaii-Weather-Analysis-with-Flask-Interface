# SQL_Advanced_Storage_and_Retrieval_with_SQL_alchemcy_and_flask

## Overview
This project uses Python and SQLalchemy to do basic climate analysis and data exploration of a sqlite climate database and excel data from Hawaii. Analysis results are in the jupyter notebook file with select results saved in the Images folder including charts showing the frequency of temperatures, the precipitation by date, and the average, max, and minimum temperature of a trip. 

### Installation and deployment:
1. Clone the repository.
2. Open the “climate_starter” Jupyter Notebook to find analysis and graphs including: precipitation by date, precipitation statistics, weather station information, record frequency at each weather station, most active stations, maximum, minimum, and average temperatures, frequency of temperatures.
3. The last two entries in the Juptyer Notebook file allow the user to enter a specific date and retrieve the average, minimum, and maximum temperatures for that date in a bar graph as well as a return of the stations by ascending precipitation over a select period of dates. 
4. Running the “app.py” file in terminal will provide a url to open in your web browser with various paths allowing you to see the available routes:
a. Stations: View all weather stations (/api/v1.0/stations)
b. Precipitation: Shows precipitation data by date (/api/v1.0/precipitation)
c. Temperature of observations (TOBs): displays temperature of each available station by date (/api/v1.0/tobs)
d. Average, max, and min tempeture of specific date within date range of data (2010-01-01 to 2017-08-23). User can enter the date in YYYY-MM-DD format after the url to obtain the average, max and minimum temperature data. (/api/v1.0/YYYY-MM-DD). The user can also find the average, max, and minimum temperatures over a time period (/api/v1.0/YYYY-MM-DD/YYYY-MM-DD).


### Technology Used:
* Python3, SQLalchemy, Matplotlib, Flask
* Jupyter Notebook, Pandas 
