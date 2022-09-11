# API-challenge

This challenges looks at the use of multiple APIs. Initially, WeatherPy looks at how different weather parameters are affected by their distance to the equator. Random coordinate points were selected from across the world. The clearest takeaway from this analysis showed a relationship between max temperature and distance to the equator. The closer one is to the equator, the higher the maximum temperature is. 

The  VacationPy script uses the data found through the WeatherPy analysis. The data is put into a heatmap showing humidity and it's relative relationship to the data. From here, an attempt to find vacation spots is made by limiting the available cities to a lower overall city count. These vacation spots then are used to find hotels near the area. When a hotel cannot be found, it is dropped from the list.
