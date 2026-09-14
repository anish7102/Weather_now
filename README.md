WeatherNow

WeatherNow is a simple and responsive weather application that allows users to search for a city and view its current weather information in real time.

The application uses the OpenWeather API to fetch live weather data and displays temperature, weather conditions, feels-like temperature, humidity, and dynamic weather icons.

Features
Search weather by city name
Display current temperature in Celsius
Dynamic weather icons based on weather conditions
Display humidity percentage
Display "Feels Like" temperature
Live date and time
Error handling for invalid city names
Clean and responsive user interface
Real-time weather data using OpenWeather API
Technologies Used
HTML5 – Structure of the application
CSS3 – Styling and responsive layout
JavaScript – Application logic and API handling
OpenWeather API – Real-time weather data
Font Awesome – Weather icons
Project Structure
WeatherNow/
│
├── index.html
├── style.css
└── README.md
API Used

WeatherNow uses the OpenWeather API to retrieve current weather information.

The application fetches data such as:

Temperature
Feels-like temperature
Humidity
Weather description
Weather condition ID

The weather condition ID is used to display an appropriate weather icon.

How It Works
Enter a city name in the search box.
Click the Get Weather button.
JavaScript sends a request to the OpenWeather API.
The API returns the current weather information.
The application displays:
Temperature
Weather condition
Feels-like temperature
Humidity
Current date and time
If the city cannot be found, an error message is displayed.
