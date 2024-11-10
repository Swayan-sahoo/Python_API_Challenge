# Python_API_Challenge
Python API Challenge - WeatherPy and VacationPy
Background
Data is a powerful tool for answering questions. Here, we use Python requests, APIs, and JSON traversals to explore a fundamental question: What is the weather like as we approach the equator?

While it may seem intuitive that the temperature increases toward the equator, this project provides the data-driven insights to prove it. Through analysis, we'll create a series of weather-based visualizations and maps to showcase relationships between weather variables and latitude.

Project Overview
This activity is divided into two main deliverables:

WeatherPy: Analyze and visualize weather data across over 500 cities worldwide.
VacationPy: Build on the weather data analysis to plan ideal vacation spots with customizable weather conditions.
Getting Started
Prerequisites
Python (3.x)
Jupyter Notebook
Libraries:
requests
pandas
matplotlib
citipy
scipy.stats
geoViews
You will also need an API Key for:

OpenWeatherMap
Geoapify
Initial Setup
Create a new repository: Name it python-api-challenge.
Clone the repository locally.
Add files and folders:
Create a directory named WeatherPy in your repo.
Inside WeatherPy, add the following files from the starter code:
api_keys.py (for API key storage)
WeatherPy.ipynb
VacationPy.ipynb
Configure .gitignore:
Add a .gitignore file to your repo to exclude sensitive files like api_keys.py:
graphql
Copy code
# Exclude API key file
api_keys.py
Project Details
Part 1: WeatherPy
This part of the project focuses on visualizing weather data for over 500 cities worldwide using the OpenWeatherMap API.

# Requirements
Scatter Plots: Use the OpenWeatherMap API to retrieve weather data and create scatter plots to showcase:
Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed
Linear Regression:
Compute and display linear regression for each variable.
Separate data by hemisphere and add regression lines and r² values to visualize relationships.
Outputs
Plots:
Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed
Analysis: Provide interpretations and insights after each plot, highlighting key patterns.
Part 2: VacationPy
In this part, use the weather data to plan potential vacation destinations by creating visualizations with ideal conditions.

## Requirements
# City Map:
Use geoViews to display all cities on a map with each city’s humidity represented by point size.
Ideal Weather Conditions:
Filter cities based on customizable ideal weather conditions.
Example criteria:
Temperature between 21-27°C
Wind speed less than 4.5 m/s
No cloudiness
# Hotel Map:
For each selected city, use the Geoapify API to locate the nearest hotel within 10 km.
Display each city with hover-over details, including hotel names and other relevant information.
Hints and Considerations
Random Coordinates: Ensure cities cover a range of latitudes to avoid regional bias.
API Familiarity: Familiarize yourself with OpenWeatherMap’s response structure to retrieve the necessary data.
Functionality: If possible, create functions for reusable tasks, such as regression calculations.
Optimization: Limit the number of API requests to avoid excessive calls and costs, especially in VacationPy.
Conclusion
By completing this project, you’ll gain a solid understanding of working with APIs and visualizing data through maps and scatter plots, further solidifying your data analytics skills.
