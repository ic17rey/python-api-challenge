# Python API Challenge - Weather

### Challenge analyzes weather conditions in relation to a city's distance from the equator.

The Weather_VacationPy folder of the python-api-challenge repository contains the code written for the challenge.  

The file called 'WeatherPy.ipynb' contains the script to run for the analysis.  

Over 500 latitudes and longitudes cities were pulled at random and the closest city to each set of random coordinates were found using CitiPy. Once the list of cities is created, weather details are called using the OpenWeatherApp API and those details are pulled into a Pandas DataFrame. The information is read into a csv file in the output_data folder.

Scatter plots are then created and displayed in the notebook. A brief analysis is included beneath each plot and the images for each are saved to the output_data folder.  

Scatter plots included are:  
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Linear regressions are done for each of the relationships once the data frame of the weather data is split into two parts, one of data for the Northern Hemisphere and one of data for the Southern Hemisphere. Following each plot including the linear regression line observations are again made. Images for all plots are saved to the output_data folder.

Linear regressions included are:
* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

Again, observations are made following each scatter plot and the cities.csv file and all images are saved to the output_data folder as the code is being run.

The challenge originally included a second part, VacationPy, that we were instructed to skip due to the use of gmaps for processing the code.

