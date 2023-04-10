# Challenge 6 - Python APIs

For this assignment, in [WeatherPy.ipynb](/WeatherPy.ipynb) I began with a random list of cities and, using OpenWeather's API, collected the current weather data for all the locations and saved it to a csv. Using the data I then plotted different values vs the latitude of the cities and preformed linear regressions to see if there were any relationship and other conclusions. Then, in [VacationPy.ipynb](/VacationPy.ipynb) used the same data to plot all the cities on a map. I then filtered the data down to a small number of locations by weather conditions and, using Geoapify API, found the nearest hotel to the city. Finally, I plotted these locations on another map.

## WeatherPy

Plots of full weather data:

Weather data was collected on April 5, 2023.

All plots have a latitude range of -90° to 90° (the full range of latitude) even though the data only goes from -60° to 80°.

Linear regressions and analysis are included in [WeatherPy.ipynb](/WeatherPy.ipynb).

![Temperature Plot](/output_data/WeatherPy_Lat_v_Temp.png)
![Humidity Plot](/output_data/WeatherPy_Lat_v_Humidity.png)
![Cloudiness Plot](/output_data/WeatherPy_Lat_v_Cloudiness.png)
![Wind Speed Plot](/output_data/WeatherPy_Lat_v_Wind.png)

## VacationPy

Plot of all the cities collected in WeatherPy.

![All Cities](/output_data/VacationPy_citites.png)

Plot of cities with "ideal weather"
- Temperature 24-30 °C ( 75-86 °F)
- Wind speed 2-10 m/s  (4-22 mph)
- Cloudiness 0-15%

![Ideal Cities](/output_data/VacationPy_citites_ideal.png)