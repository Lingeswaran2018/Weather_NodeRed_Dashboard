# Weather Application - Node-RED

## Project Overview
This project is a Node-RED-based weather application that retrieves weather data from OpenWeather API based on user-provided locations. The application features a dashboard with multiple tabs, allowing users to view real-time weather updates, set warning limits, and visualize historical data with charts.

## Features
- Users can enter a location using coordinates or city and country.
- Weather updates every 30 seconds by default, with an option to modify the interval.
- Displays temperature, humidity, pressure, wind speed, wind direction, sunrise, and sunset times.
- Audio description feature to read weather details aloud.
- Interactive charts displaying past hour data for temperature, humidity, and wind speed.
- Warning system with notifications for exceeded thresholds.

## Installation & Setup
1. Install [Node-RED](https://nodered.org/docs/getting-started/)
2. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/weather-app-node-red.git
   ```
3. Navigate to the project directory:
   ```sh
   cd weather-app-node-red
   ```
4. Install required dependencies:
   ```sh
   npm install
   ```
5. Start Node-RED:
   ```sh
   node-red
   ```
6. Import the provided `.json` file into Node-RED via the import feature.
7. Deploy and start using the application.


## Demo Video & Screenshots
https://github.com/user-attachments/assets/8b6d3127-2d11-4e9e-8fc8-8d4cc1a4a3f1

## Usage
- Open the dashboard in a web browser.
- Enter location details and submit.
- Adjust refresh intervals and enable/disable features in the settings tab.
- Monitor real-time and past hour weather conditions.
- Receive alerts when parameters exceed the defined limits.


### Here I have Attached Some  Screenshots
![WeatherTab](https://github.com/user-attachments/assets/3e22530c-10f0-4e80-a4b3-efe436d62067)
![SettingTab](https://github.com/user-attachments/assets/de5685b9-e548-42f3-81a7-000dc56737df)
![ChartsTab](https://github.com/user-attachments/assets/8e7e8122-2799-4a7c-be7e-beb428ebdb16)
![Notification](https://github.com/user-attachments/assets/56685791-375f-448f-92e0-1d1ed71ae665)



---

