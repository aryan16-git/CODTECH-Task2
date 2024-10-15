**Name:** ARYAN GUPTA
**Company:** CODTECH IT SOLUTIONS
**ID:** CT08DS8192
**Domain:** Web Development
**Duration:** September to October 2024
**Mentor:** NEELA SANTHU
## Weather Forecast App

This is a simple weather forecast application built using HTML, CSS, and JavaScript. The app allows users to enter a location and receive real-time weather information such as temperature, humidity, wind speed, and a brief description of the weather conditions. It uses the [OpenWeatherMap API](https://openweathermap.org/) to fetch weather data.

### Features

- **Location-Based Weather:** Enter a city name to get the current weather conditions.
- **Temperature Display:** Shows the temperature in Celsius.
- **Weather Description:** Provides a brief description (e.g., clear sky, rain, etc.).
- **Humidity and Wind Speed:** Displays the humidity percentage and wind speed.
- **Dynamic Weather Images:** The background image changes based on the weather condition (e.g., clouds, clear sky, rain).
- **Error Handling:** Displays an error message when the location is not found.

### Technologies Used

- **HTML:** Structure of the web page.
- **CSS:** Styling the application, including layout and design.
- **JavaScript:** Logic for fetching data from the OpenWeatherMap API and updating the UI based on the results.

### How It Works

1. The user enters a city name into the input box.
2. When the search button is clicked, the app sends a request to the OpenWeatherMap API to retrieve weather data for that location.
3. If the location is valid, the app displays the temperature, weather description, humidity, and wind speed. The background image changes according to the weather condition.
4. If the location is not found, an error message is displayed.

### Project Structure

- **HTML (`wheatherforecast.html`)**: Contains the structure of the app, including the input field for the city name and the display sections for weather details.
- **CSS (`wheatherforecast.css`)**: Provides styling for the app, making it responsive and visually appealing.
- **JavaScript (`wheatherforecast.js`)**: Handles fetching data from the OpenWeatherMap API and dynamically updating the weather details in the UI.

## How to Run

1. Clone this repository.
2. Open `wheatherforecast.html` in your browser.
3. Enter a city name in the input field and click the search button to see the weather information.
