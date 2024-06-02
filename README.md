# Weather_app
A simple weather application built using React JS and the OpenWeather API. Users can see the current weather based on their current location or by entering a location of their choice.

## Features
- Display current weather for the user's location using geolocation.
- Allow users to search for weather in any city by entering the location.
- Show weather details including temperature, humidity, wind speed, and weather conditions.
- Responsive design for use on both desktop and mobile devices.

## Demo
https://weather-5qgduu5vv-harsh1519s-projects.vercel.app/

## Screenshots
![Weather_app](https://github.com/harsh1519/Weather_app/assets/98206466/3b47230e-c9d2-4cdc-bdfd-9849dcc31e54)

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/weather-app.git
    cd weather-app
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Obtain an API key from [OpenWeather](https://openweathermap.org/api) and add it to your `.env` file:
    ```env
    REACT_APP_WEATHER_API_KEY=your_api_key_here
    ```

4. Start the development server:
    ```bash
    npm start
    ```

5. Open your browser and navigate to `http://localhost:3000`.

## Usage
1. Current Location Weather:
    - When the application loads, it will prompt the user for permission to access their location.
    - If the user grants permission, the app will display the current weather for their location.

2. Search Weather by Location:
    - Users can enter a city name in the search bar and click the search button.
    - The app will display the weather information for the entered cit
