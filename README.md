# Weather App - React + Vite 

This project is a Weather App built using React and Vite. It provides users with current weather information and forecasts based on city search or current location.

## Key Features 🚀

- Search weather by city name.
- Display current weather details including temperature, humidity, pressure, wind speed, visibility, sunrise, and sunset.
- Shows hourly and daily forecasts.
- Handle errors for invalid city names gracefully.
- Uses OpenWeather API for fetching current weather data.
- Uses the WeatherBit API to provide the forecast data.
- Responsive and user-friendly UI styled with Tailwind CSS.
- Utilizes React hooks for state management and side effects.

## Technologies Used ⚙️

- React + Vite
- OpenWeather API + WeatherBit API
- Tailwind CSS

## Setup and Usage 💻

1. Clone the repository.
2. Install dependencies using `npm install`.
3. Create a `.env` file in the root directory and add your OpenWeather and WeatherBit API key:
   ```
   VITE_WEATHER_API = your_api_key_here
   VITE_WEATHERBIT_API = your_api_key_here
   ```
4. Run the development server using:
   ```
   npm run dev
   ```
5. Open the app in your browser at the provided local server address.

## Notes

- Ensure you have a valid OpenWeather and WeatherBit API key to fetch weather data.
- The app fetches location data based on IP. So you must have an internet connection.
