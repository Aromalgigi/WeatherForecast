# WeatherForecast

## Overview
A Full-Stack Weather App displays real-time weather data for a city. Angular is used for user interaction, and Spring Boot is used to fetch weather data from OpenWeather API. AWS server is used for the deployment of the application.

## Technologies Used
- Angular: Frontend framework for building user interfaces.
- Spring Boot: Backend framework for building RESTful APIs.
- OpenWeather API: External API to fetch weather data.
- AWS:For hosting the web application

## Getting Started
Follow the steps below to set up and run the Weather App locally.
1. Clone the repository:
2. Provide the OpenWeather API Key:
  - Replace `openweather_api_key` in `application.properties`.
3. Build the project:
4. Run the application
5. Access the API
    -Angular using: `ng serve`

Replace `{city}` with the name of the city for which you want to get the weather data.

## API Endpoint
The Weather App provides a single API endpoint to get weather data for a specific city:

- **Endpoint:** `/weather?{city}`
- **Method:** GET
- **Parameters:** `{city}` (required) - The name of the city for which you want to get weather data.


## Link
To access
-http://ngwebapplication.s3-website.eu-north-1.amazonaws.com/


