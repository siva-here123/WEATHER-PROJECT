
# Weather App

Welcome to the Weather App! This project is designed to provide you with real-time weather updates using the **Open-Meteo API**. You can easily check the weather for your current location through geolocation or by searching for a specific city. Plus, the app lets you compare weather conditions across different cities in a handy table.

## Features

* **Get Weather by Current Location**: The app uses the **Geolocation API** to find your latitude and longitude. From there, it gets your city name using the **BigDataCloud API** and fetches the weather details with the **Open-Meteo API**.

* **Manual City Search**: If the app can’t access your location, no worries! You can simply type in a city name, and it will grab the coordinates using the **Nominatim OpenStreetMap API**.

* **Weather Data Display**: You’ll see key weather information like temperature, humidity, wind speed, and more — all updated regularly to keep you informed.

* **Compare Cities**: Want to see how the weather stacks up in different places? The app shows weather conditions for multiple cities side by side in a clear, easy-to-read table.

* **Responsive Design**: The app is designed to work smoothly on desktops, tablets, and mobile devices — so you can check the weather wherever you are.

* **Error Handling**: Friendly messages guide you if location access is denied or if a city name can’t be found, helping you stay on track.

## How It Works

1. **Automatic Location Detection**:

   * The app starts by trying to get your latitude and longitude through the **Geolocation API**.
   * If it succeeds, it converts those coordinates into your city name using the **BigDataCloud Reverse Geocoding API**.
   * Finally, it retrieves the weather data from the **Open-Meteo API** based on your coordinates.

2. **Manual City Search**:

   * If geolocation isn’t available or is blocked, you can enter a city name manually.
   * The app then fetches the coordinates for that city using the **Nominatim OpenStreetMap API**.
   * Those coordinates are used to get the weather data from the **Open-Meteo API**.

3. **Weather Comparison Table**:

   * You can easily compare the weather in multiple cities at once.
   * The app gathers weather data for various locations and presents it in a well-organized table.

## Technologies Used

* **HTML, CSS, JavaScript** – For building the frontend and ensuring smooth user experience
* **Geolocation API** – To get your current coordinates
* **BigDataCloud Reverse Geocoding API** – To turn latitude and longitude into a city name
* **Nominatim OpenStreetMap API** – To find latitude and longitude for a city you search
* **Open-Meteo API** – For retrieving accurate and up-to-date weather data
* **Fetch API** – To handle API requests and responses efficiently

## Future Improvements

* Add hourly and daily forecast views for more detailed weather insights.
* Include weather condition icons to make the data more visually engaging.
* Implement user preferences for units (Celsius/Fahrenheit) and themes (light/dark mode).
* Add notifications or alerts for severe weather conditions.

---

I’d **love to hear your comments or any suggestions** to make this app even better!

---
