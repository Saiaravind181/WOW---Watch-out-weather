# WOW --Watch-out-weather

## Overview

This Weather App is a web application that provides real-time weather information for various cities. It utilizes the Weather API to fetch data and displays it in a user-friendly interface. The app is built with HTML, CSS, and JavaScript.

## Features

- **Real-time Weather Data:** Fetches current weather conditions, including temperature, humidity, wind speed, and weather conditions.
- **City Search:** Users can input a city name to get its weather information.
- **Responsive Design:** The app is designed to be mobile-friendly, adapting to different screen sizes.
- **Dynamic Backgrounds:** Changes the background image based on the current weather conditions (clear, cloudy, rainy, snowy).

## Technologies Used

- **HTML:** Structure of the web application.
- **CSS:** Styling of the application, including responsive design.
- **JavaScript:** Functionality for fetching weather data and updating the UI dynamically.
- **Weather API:** External API to retrieve weather information.

## Installation

1. Clone the repository or download the files.
2. Open the `index.html` file in your web browser.

## Usage

1. Enter a city name in the search bar and press the submit button.
2. The app will fetch the weather data for the specified city and display it.

## File Structure

/weather-app
│
├── index.html # Main HTML file
├── style.css # CSS styles for the app
├── script.js # JavaScript for fetching and displaying weather data
└── /images # Directory containing background images
├── day
├── night
└── icons


## CSS Overview

The `style.css` file contains styles for the app, including layout, fonts, colors, and responsive design. Key styles include:

- **Body Styles:** Sets the font family and background color.
- **Weather App Container:** Styles for the main app container, including positioning and background images.
- **Panel Styles:** Styles for the side panel containing city selection and search functionality.

## JavaScript Overview

The `script.js` file handles the following functionalities:

- Fetching weather data from the Weather API.
- Updating the UI with the fetched data.
- Handling user input for city search.
- Managing background images based on weather conditions.

## API Key

To use the Weather API, you will need to sign up and obtain your own API key. Replace the placeholder API key in the `fetchWeatherData` function with your own.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any improvements or bug fixes.

## License

This project is licensed under the MIT License.
