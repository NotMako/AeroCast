# AeroCast
This React Native mobile application provides real-time weather data, location-based forecasts, and city search functionality using the OpenWeather API. It delivers a clean, dynamic user interface that updates based on current weather conditions and supports persistent storage of user-selected cities.

The app automatically detects the user’s location, displays current weather conditions, and provides a 7-day forecast with daily high and low temperatures. It also includes an intelligent city search system that suggests locations and sorts them based on proximity to the user.

Features:
- Fetches real-time weather data using OpenWeather API
- Detects user location using Expo Location (GPS)
- City search with autocomplete and nearest-distance sorting
- Displays current temperature, condition, and weather icon
- 7-day forecast with daily high/low temperatures
- Dynamic background images based on weather conditions
- Save favorite cities using AsyncStorage
- Clean, responsive mobile UI built with React Native

Technical Details:
- Built with React Native (Expo)
- Uses REST APIs for weather and geocoding data
- Implements asynchronous data fetching with fetch
- Processes JSON responses for real-time updates
- Uses FlatList for optimized rendering of forecast data
- Implements distance calculation (Haversine formula) for sorting locations
- Handles API errors and edge cases (invalid city, missing data)

Version Information
Version 1: 
- Basic weather search by city name 
- Displays current temperature and condition

Version 2: 
- Added GPS-based location detection
- Implemented city autocomplete with nearest sorting
- Added 7-day forecast with daily min/max temperatures
- Integrated dynamic weather-based backgrounds
- Added persistent storage for saved cities

Notes:
- Requires an OpenWeather API key
- Free API tier has rate limits and forecast granularity restrictions (3-hour intervals)
- Forecast data is approximated into daily highs/lows from available intervals
