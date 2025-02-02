## Weather App

A simple weather application built using HTML, CSS, and JavaScript. This app fetches real-time weather data from a weather API and displays it in a user-friendly interface.

## Features

- **Current Weather**: Displays the current temperature, weather condition, humidity, and wind speed.
- **Location Search**: Allows users to search for weather information by city name.
- **Responsive Design**: The app is fully responsive and works on all devices (desktop, tablet, and mobile).

## Technologies Used

- **HTML**: For structuring the web page.
- **CSS**: For styling and layout.
- **JavaScript**: For fetching data from the API and dynamically updating the DOM.
- **OpenWeatherMap API**: For retrieving real-time weather data.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/abbhhhiiiii/weather-app.git
   ```
2. Open the project folder:
   ```bash
   cd weather-app
   ```
3. Open the `welcome.html` file in your browser.
4. then connect the file to the index.html

## API Key Setup

To use the OpenWeatherMap API, you need to sign up for a free API key at [OpenWeatherMap](https://openweathermap.org/api).

1. Create an account on OpenWeatherMap.
2. Generate an API key.
3. Replace `b4d251c1a2875ee4d912e9360b620103` in the `script.js` file with your actual API key:
   ```javascript
   const apiKey = 'b4d251c1a2875ee4d912e9360b620103';
   ```

## Live Demo

Check out the live demo of the app [here](https://weather-app-two-sigma-31.vercel.app/).

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeatureName`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeatureName`).
5. Open a pull request.
