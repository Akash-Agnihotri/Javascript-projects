# Weather API Web Application

This is a simple web application (https://akash-agnihotri.github.io/Weather-API-Web-Application/) that allows users to check the weather for a specific location. The application uses the OpenWeatherMap API to retrieve weather data for the entered location and displays it on the webpage.

## Table of Contents
- [Features](#features)
- [Usage](#usage)
- [Styling](#styling)
- [API Key](#api-key)

## Features
- Users can enter a location in the input field and click the search button to retrieve weather information for that location.
- The application displays the current temperature, city name, humidity, and wind speed for the specified location.
- It also displays a weather icon based on the current weather conditions (e.g., cloudy, clear, rainy).

## Usage
1. Clone this repository to your local machine or download the HTML and CSS files.
2. Open the `index.html` file in a web browser.

![Screenshot] ![Screenshot](https://github.com/Akash-Agnihotri/Weather-API-Web-Application/assets/143778749/3b8b2920-23a3-4004-bf37-fb57f036a67d)


3. Enter a location in the input field and click the search button.
4. The weather information for the specified location will be displayed on the webpage.

## Styling
The application features a visually appealing card layout with a background gradient animation. The card is centered on the page and includes input fields for searching, weather information display, and weather icons.

## API Key
To make API requests to OpenWeatherMap, an API key is required.You should obtain your own API key by signing up on the [OpenWeatherMap website](https://openweathermap.org/api) and replace the placeholder with your actual API key.

```javascript
const apiKey = "YOUR_API_KEY_HERE";
```

Please note that this application has limited error handling and assumes valid city names for simplicity. If an invalid city name is entered, it will display an error message.

Feel free to modify and enhance this code to suit your needs or expand its functionality. Enjoy checking the weather!
