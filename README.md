Live Demo
Check out the live application here: Weather App Live Demo

Overview
This Weather App is a sleek and modern frontend application designed to provide users with up-to-date weather information based on their input. It is built using HTML, CSS, and JavaScript (React framework) and integrates with the Open Weather API to deliver real-time weather data.

Features

Real-Time Weather Updates: Displays the current weather, location, temperature, date, and time.
City and Zip Code Search: Allows users to fetch weather information by entering a city name or zip code.
Fully Responsive Design: Optimized for viewing on desktops, tablets, and mobile devices.
Theme Customization: Switch between dark and light modes for optimal visibility in different environments.
Multi-City Support: Check weather information for multiple cities at the same time.
Comprehensive Weather Data: Includes additional details such as humidity, wind speed, weather conditions, and more.
Installation and Setup

Clone the repository:
bash
Copy code
git clone <repository-url>
cd weather-app
Install the project dependencies:
bash
Copy code
npm install
Set up your API key by creating a .env file in the root directory and adding your Open Weather API key:
makefile
Copy code
REACT_APP_OPEN_WEATHER_API_KEY=your_api_key
Start the development server:
bash
Copy code
npm start
Open http://localhost:3000 in your web browser to view the application.
Usage

When the app launches, it requests permission to access your location to display weather data for your current location.
Enter a city name or zip code in the search bar and press Enter or click the search icon to retrieve weather data for a specific location.
The app will show the current weather, temperature, "feels like" temperature, humidity, high and low temperatures, wind speed, date, and time for the selected location.
Toggle between dark and light themes using the theme switcher.
To view weather for additional locations, enter another city or zip code and repeat the process.
Technologies Used

React: For building a dynamic and interactive user interface.
fetch: For making HTTP requests to the Open Weather API.
Open Weather API: For accessing current weather data.
Project Structure

src/components: Contains reusable React components (SearchBar, WeatherCard, ThemeToggle.js, Header.js, Navbar.js).
src/styles: CSS modules for component styling.
src/App.js: Main application component.
