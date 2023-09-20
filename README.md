# Weather Tracker

This is a simple project used for learning how to consume APIs using the Go programming language. This project utilizes the OpenWeatherMap API to retrieve weather data based on the provided city name.

## Features

- Consume the OpenWeatherMap API to fetch weather data based on city names.
- Display weather data in JSON format.

## How to Use

1. Clone this repository:
    ```
    git clone https://github.com/alfauzan003/golang-weather-tracker.git
    ```

2. Navigate to the project directory:
    ```
    cd golang-weather-tracker
    ```

3. Create a .apiConfig file and add your OpenWeatherMap API configuration. Example configuration:
    ```
    {
        "OpenWeatherMapApiKey": "YOUR_API_KEY_HERE"
    }
    ```

4. go run main.go
    ```
    http://localhost:8000/weather/{CITY_NAME}
    ```