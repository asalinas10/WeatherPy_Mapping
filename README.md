# WeatherPy

In this project I used Python, API's, and JSON transversals to analyze weather data.

This project has two parts. In the first part (WeatherPy), I created a Python script to visualize the weather of over 500 cities of varying distances from the equator called WeatherPy. I used the citipy Python library, the OpenWeatherMap API, and used problem-solving skills to create a representative model of weather across cities.

In this the second part (VacationPy), I used weather data skills to get weather data to plan a future vacation. I also used Jupyter notebooks, the geoViews Python library, and the Geoapify API. My main tasks was to use the Geoapify API and the geoViews Python library and employ my Python skills to create map visualizations.

# Summary

WeatherPy:

1.  Create Plots to Showcase the Relationship Between Weather Variables and Latitude

    - To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:

        - Latitude vs. Temperature

        - Latitude vs. Humidity

        - Latitude vs. Cloudiness

        - Latitude vs. Wind Speed

![Alt text](<Screen Shot 2024-01-04 at 12.54.20 PM.png>)

2. Compute Linear Regression for Each Relationship

    - To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots.

    - You should create the following plots:

        - Northern Hemisphere: Temperature vs. Latitude

        - Southern Hemisphere: Temperature vs. Latitude

        -  Northern Hemisphere: Humidity vs. Latitude

        - Southern Hemisphere: Humidity vs. Latitude

        - Northern Hemisphere: Cloudiness vs. Latitude

        - Southern Hemisphere: Cloudiness vs. Latitude

        - Northern Hemisphere: Wind Speed vs. Latitude

        - Southern Hemisphere: Wind Speed vs. Latitude

![Alt text](<Screen Shot 2024-01-04 at 1.23.47 PM.png>)

VacationPy:

1. Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.

![Alt text](<Screen Shot 2024-01-04 at 2.06.17 PM.png>)

2. Narrow down the city_data_df DataFrame to find your ideal weather condition.

3. Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

4. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.

5. Add the hotel name and the country as additional information in the hover message for each city on the map as in the following image:

![Alt text](<Screen Shot 2024-01-04 at 2.14.15 PM.png>)






