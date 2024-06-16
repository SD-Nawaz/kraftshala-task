# Weather Application


![image](https://github.com/pravesh2892/kraftshala-assignment/assets/112716122/b6205d56-6f9e-47d1-9244-f9e854be532b)


![image](https://github.com/pravesh2892/kraftshala-assignment/assets/112716122/69177f66-e838-4d89-83f1-abfb1761ef8a)




## Live Demo

Explore the live application: [Weather Insight Live Demo](https://kraftshala-task-nawaz085-sayed-nawazs-projects.vercel.app/)

## Overview

The Weather Forecast App is a comprehensive tool designed to provide detailed weather predictions and insights for travelers and outdoor enthusiasts. It leverages advanced forecasting algorithms and integrates with various weather data sources to deliver accurate and timely information.

## Features

- **Hourly and Daily Forecasts**: Offers detailed hourly and daily weather forecasts, including temperature trends, precipitation chances, and wind conditions.
- **Interactive Map View**: Visualize weather patterns and trends using an interactive map interface, with overlays for radar, satellite imagery, and severe weather alerts.
- **Travel Planner**: Plan trips effectively with weather forecasts for multiple destinations, ensuring you're prepared for varying conditions along your route.
- **Dark Mode**: Toggle between dark and light themes for comfortable viewing in any environment.
- **Community Reports**: Enable users to submit real-time weather observations and photos, fostering a community-driven approach to weather reporting.
- **Accessibility Features**: Designed with accessibility in mind, including support for screen readers and high-contrast modes.

## Installation and Setup
1. Clone the repository:
2. Install dependencies:
3. Create a `.env` file in the root directory and add your Open Weather API key:
4. Start the development server:
5. Open [http://localhost:3000](http://localhost:3000) to view the app in your browser.

## Usage

1. On launch, the app displays weather information for your current location (requires location permission).
2. Enter a city name or zip code in the search bar and press Enter or click the search icon.
3. The app will display the current weather, temperature,feels like, humidity, max temperature, min-temrature, wind speed, date,time for the entered location.
4. Use the toggle switch to change between dark and light modes.
5. To add multiple locations, click on the search bar, enter another location, and repeat.

## Technologies Used

- **React**: For building the user interface.
- **fetch**: For making API requests.
- **Open Weather API**: For fetching weather data.

## Project Structure

- `src/components`: React components (SearchBar, WeatherCard, DarkModeToggle.js, Logo.js, Navbar.js).
- `src/App.css`: CSS module  for styling components.
- `src/App.js`: Main application component.
 
