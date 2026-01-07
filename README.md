# Weather-infomation

Project Overview :

- This project is a simple Weather Application built using HTML, CSS, and JavaScript. It allows users to search for any city and get real-time weather information such as :

🌡️ Temperature (in °C)

💧 Humidity

🌬️ Wind Speed

- The weather data is fetched dynamically from the OpenWeatherMap API.


Technologies Used :

- HTML5 – Structure of the web page
- CSS3 – Styling and responsive design
- JavaScript (ES6) – API integration and dynamic data handling
- OpenWeatherMap API – Real-time weather data


Project Structure :

Weather-App/ │ ├── index.html # Main HTML file ├── style.css # Styling file ├── README.md # Project documentation


Features :

- Search weather by city name


Displays:

- Temperature in Celsius
- Humidity percentage
- Wind speed (km/h)
- Clean and simple UI design
- Real-time API data fetching


API Used :

- OpenWeatherMap API


Example API format used in the project:

- https://api.openweathermap.org/data/2.5/weather?units=metric&q=city_name&appid=API_KEY <-- Make sure to replace the API key with your own key if deploying publicly.-->


How the Application Works (Step-by-Step) :

- User enters a city name in the search box.
- On clicking the search button, JavaScript triggers the checkWeather() function.
- The function calls the OpenWeatherMap API using fetch().
- Weather data is received in JSON format.
- The following details are updated dynamically on the UI :

< City name

< Temperature

< Humidity

< Wind speed

<-- LInk of weather-->

file:///D:/all%20projects/weather%20system/weather%20system%20neha/index.html
