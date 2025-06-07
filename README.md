# WeatherApp
In this project, a weather tracking application was developed using data structures such as Binary Search Tree, Queue, Stack, LinkedList, and Graph. The user interface was designed with JavaFX.

# JavaFX Weather App (with OpenWeatherMap API Integration)

This project is a weather tracking application built using JavaFX. Users can enter the name of a city to view current weather conditions, hourly forecasts, 5-day forecasts, and detailed weather data for surrounding districts. All data is retrieved via the [OpenWeatherMap](https://openweathermap.org/) API.


## API Key Required

The application uses the OpenWeatherMap API and requires an API key to function. To get your API key:

1. Go to [https://home.openweathermap.org/api_keys](https://home.openweathermap.org/api_keys)  
2. Register for a free account and generate an API key  
3. Replace the following line in `WeatherService.java` with your API key:

```java
private static final String API_KEY = "YOUR_API_KEY_HERE";
