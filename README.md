# Weather App 🌦️

## Overview
This Weather App is designed to provide real-time weather information based on the user's location. Built with Swift, the app integrates with the Weather API and MapKit to display weather data and forecasts directly on a map.

## Features
- **Map Integration**: Uses MapKit to display weather conditions on a map with custom annotations.
- **Real-Time Weather Data**: Fetches current weather conditions, including temperature, high/low, and weather icons, from the Weather API.
- **Dynamic Updates**: Automatically updates weather information based on the user's current location or selected location.
- **Forecast Display**: Shows temperature and weather forecasts for the day.

## Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/rajrana43/Weather-app.git

## Open in Xcode:
- Open the `.xcodeproj` file in Xcode.

## Install dependencies (if any):
- Use Swift Package Manager or CocoaPods to install any necessary dependencies.

## Build and Run:
- Select a simulator or connected device, then click the Run button in Xcode to build and launch the app.

## Usage 📲
1. **Launch the app**.
2. A new location's weather is automatically fetched and displayed on the map.
3. Tap on the map to select a different location and view its weather.
4. The map will update with an annotation showing the selected location's weather data.

## Code Overview 📝
- **ViewController.swift**: Handles the main logic, including map setup, fetching weather data, and displaying annotations.
- **DetailsViewController.swift**: Manages additional details and settings.
- **WeatherResponse.swift**: Contains data models for parsing the weather API response.
- **LocationItem.swift**: Represents a location's weather data and coordinates.

## Contributing 🤝
Contributions are welcome! If you have any suggestions, improvements, or bug fixes, feel free to submit a pull request.

### Contact 📧
If you have any questions or feedback, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/raj-rana-a9b8a5138/) or open an issue on this repository.
