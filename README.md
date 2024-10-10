# Weather App
## Table of Contents

- [Description](#description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Integration](#api-integration)
- [Continued development](#Continued-development)
- [Resouces](#Resources)
- [Credit](#Credit)

## Description

The Weather App is a user-friendly application built with React that allows users to search for the current weather conditions of any city around the world. The application fetches data from the OpenWeatherMap API and displays essential weather information, including temperature, humidity, and wind speed. 

In the context of the Weather App, API calls are essential for retrieving weather information based on user input. The application primarily uses the following types of HTTP requests:

- **GET Request**: 
  - The app makes a GET request to the OpenWeatherMap API when a user searches for a city. This request retrieves weather data, including temperature, humidity, wind speed, and weather conditions (e.g., clear, rainy, snowy).
  - Example URL for a GET request:
    ```
    https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units=metric
    ```

- **POST Request**: 
  - While this particular application does not implement POST requests, they are commonly used to send data to a server. For example, in a scenario where users could save their favorite cities or settings, a POST request could be used to send this data to a backend service.

- **Response Handling**:
  - The application processes the JSON response returned by the GET request. It extracts the relevant weather information, such as temperature and humidity, and updates the user interface to display this data dynamically. 
  - If the API responds with an error (e.g., city not found), the app alerts the user and handles the error gracefully.

By integrating API calls, the Weather App provides real-time updates and a seamless user experience, making it easy for users to access weather information based on their preferred locations.

## Features

- **City Search**: Users can enter any city name to retrieve the current weather information.
- **Dynamic Icons**: Displays weather condition icons based on the API response.
- **Responsive Design**: Adaptable layout for different screen sizes.
- **Default City**: Automatically fetches the weather for Lagos on initial load.

## Technologies Used

- **React**: A JavaScript library for building user interfaces.
- **CSS**: For styling the application.
- **OpenWeatherMap API**: For fetching weather data.

## Installation

To get a local copy of the Weather App up and running, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/chubicode/weatherapp.git
2. Navigate to the project directory:

cd weatherapp

3. Install the dependencies:

npm install

4. Create a .env file in the root directory and add your OpenWeatherMap API key:
VITE_APP_ID=your_api_key_here

##Usage
Usage
1. Start the development server:

npm start

2. Open your browser and go to http://localhost:3000 to view the app.

3. Enter the name of a city in the search bar and click the search icon to retrieve the weather data.

## API Integration

The application utilizes the OpenWeatherMap API to fetch weather data. The API endpoint used is:
https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units=metric

Parameters:

q: The name of the city to search for.

appid: Your OpenWeatherMap API key.

units: The unit of measurement (metric for Celsius).

The response contains various weather data, which is then processed and displayed in the app.

## Continued development 

- Consuming APIs

- CSS Grid

- React

## Useful resources 

youtube.com/watch?v=zs1Nq2s_uy4&t=14s

## Credit

Github- https://github.com/chubicode/

yotube- GreatStack




   
   
