# weather_app
This is a Python script that uses the OpenWeatherMap API to fetch real-time weather data for multiple cities. It allows you to retrieve key weather details, such as the temperature, weather conditions, and humidity, and display them in a well-structured, easy-to-understand format. This script is a great starting point for anyone looking to get hands-on experience with working with APIs, processing data, and displaying it clearly.

The script sends requests to the OpenWeatherMap API, parses the data, and prints weather reports directly to the console. It can be easily extended to support additional cities, weather parameters, or even integrate with a more interactive frontend if needed.

* Features
Real-Time Weather Data: Fetch live weather for multiple cities.
City-Specific Reports: Modify the list of cities to get data for specific locations.
Weather Metrics: Displays temperature (Celsius), weather conditions, and humidity.
Error Handling: Gracefully handles API request failures and provides fallback messages.
Clear Output: Data displayed in a structured and easy-to-read format.
Extensibility: Easily add cities, new weather parameters, or use the data for analysis/visualizations.

Technologies Used
Python: The main programming language used to write the script.
Requests: A Python library used to send HTTP requests to the OpenWeatherMap API and retrieve weather data.
Pandas: For potential future data processing and structuring.
Matplotlib: (Optional) To visualize the weather data in charts or graphs.
OpenWeatherMap API: The API used to fetch weather data. You will need to sign up for an API key on their platform.


🌐 OpenWeatherMap API
How It Works:
1)API Request: For each city in the list, the script sends a request to the OpenWeatherMap API with the city name and an API key.
2)Response Handling: The API returns a JSON response with weather data for the city, which is then parsed.
3)Data Extraction: The script extracts important weather details, such as temperature, weather condition, and humidity, and stores them.
4)Display: The weather data for each city is printed to the console.





