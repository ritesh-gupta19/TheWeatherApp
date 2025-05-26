# The Weather App

A basic Android weather app built with Kotlin and Jetpack Compose. It takes a city name as input and displays current weather information including temperature, humidity, and a weather description.

## Features

- Input any city name to get weather data.
- Displays the current temperature in Celsius.
- Shows the current humidity level.
- Confirms the city name in the results.
- Displays a brief weather description (e.g., Clear Sky, Rain, Clouds).

## How to Use

1. Open the app on your Android device.
2. Enter the name of the city in the input field.
3. Press the search button to fetch the current weather.
4. View the displayed temperature, humidity, city name, and weather description on the screen.

## Screenshots
<p float="left">
  <img src="https://github.com/user-attachments/assets/276029c2-b3a1-4edf-8ba2-8dc0221fca23" width="300" style="margin-right: 10px;" />
  <img src="https://github.com/user-attachments/assets/3dc0674e-5a33-411f-965a-6258a46bedfd" width="300" />
</p>

## Technologies Used

This project is built with a modern Android development stack and best practices.

- **UI:** Jetpack Compose - For building the app's user interface declaratively.
- **Language:** Kotlin
- **Architecture:** MVVM (Model-View-ViewModel) and Android Jetpack ViewModel - To manage UI-related data in a lifecycle-conscious way.
- **Asynchronous Programming:** Kotlin Coroutines - For managing background tasks and API calls efficiently.
- **Networking:**
  - Retrofit - A type-safe HTTP client to communicate with the API.
  - Gson - To parse JSON data from the API into Kotlin data classes.
- **Weather Data Provider:** OpenWeatherMap API

## Setup & Installation

To get a local copy up and running, follow these simple steps.

### Clone the repository

```
git clone https://github.com/ritesh-gupta19/TheWeatherApp.git
```

### Open in Android Studio
Open Android Studio and select File > Open. Navigate to the cloned directory and open the project.

### Get and Add an API Key
Sign up on OpenWeatherMap to get your free API key. Add the API Key at ' val apiKey = "My_API_KEY"'

### Build and Run
Build the project and run it on an Android emulator or a physical device.

## Notes
An internet connection is required to fetch weather data.

The app currently supports searching for weather by city name only.

