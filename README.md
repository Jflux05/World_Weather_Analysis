# World_Weather_Analysis

## Project Overview:
In this analysis, we look at weather patterns from 2000 randomly selected cities around the world and offer unique insights (destinations, hotels, and travel routes) to travelers looking to book a trip, based on the users climate preferences. There are three folders here that offer different levels of analysis: Weather_Database, Vacation_Search, and Vacation_Itinerary.

### Weather_DataBase:
The Open Weather Map API was utilized to pull weather stats from cities around the world generate the files in this folder. 

- **Deliverable 1: Generate 2000 Random Locations** 
    - [Weather_Database.ipynb](Weather_Database.ipynb) was created and used to generate 2,000 random sets of latitudes and longitudes, which are then stored in [WeatherPy_Database.csv](Weather_Database/WeatherPy_Database.csv) after retrieving information regarding the closest cities and weather information.

    - [WeatherPy_Database.csv](Weather_Database/WeatherPy_Database.csv) provides the following weather stats from 699 cities around the world:
        1. Maximum Temperature
        2. Cloudiness
        3. Wind Speed
        4. Humidity
        5. Current Weather Description

### Vacation_Search: 
Here Weather_Database insights and used Google Maps API to plot different travel destinations with a hotel at each location.

- **Deliverable 2: (Create a Customer Travel Destinations Map)**
   - With [Vacation_Search.ipynb](Vacation_Search.ipynb) we created the [WeatherPy_Vacation.csv](Vacation_Search/WeatherPy_Vacation.csv) to determine locations matching the user inputs and provide a list of hotels closets to the chosen coordinates. 

The screenshot below shows the locations of all the places in the database that have an daily maximum temperature between 70 and 98 degrees fahrenheit.
![WeatherPy_vacation_map](https://github.com/Jflux05/World_Weather_Analysis/blob/1b011834b9d845a68c46fa44ea2ce5d15b52ce82/Vacation_Search/WeatherPy_vacation_map.png)

### Vacation_Itinerary: 
Here  Vacation_Search information and the Google Maps directions API we utilized to create a vacation itinerary. For example, the image below shows a 4 stop itinerary in Central America that features Acapulco, Mexico; Kantunilkin, Mexico; Ocos, Guatemala; and Laguna De Perlas, Nicaragua.

[WeatherPy_Travel_Vacation_Map](Vacation_Itinerary/WeatherPy_travel_map.png)

The following image displays a hotel at each location from the itinerary:
[WeatehrPY_Travel_Map_Markers](
