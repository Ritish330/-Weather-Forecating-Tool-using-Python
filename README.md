# -Weather-Forecating-Tool-using-Python

This project is a weather forecasting tool implemented in Python. It utilizes the OpenWeather API to retrieve weather data for a given location and displays the temperature, humidity, and weather description.

## Description
The Weather Forecasting Tool is a simple Python script that fetches weather information using the OpenWeather API. By providing the desired location, the script retrieves the current weather data, including the temperature, humidity, and weather description. This tool can be useful for quickly checking the weather conditions of a particular location.

## Prerequisites
To run this project, you need to have the following:

- Python: Make sure you have Python installed on your system. You can download it from the official Python website: [Python.org](https://www.python.org/downloads/)

## Installation
1. Clone the repository:
   ```shell
   git clone https://github.com/your-username/weather-forecast-tool.git
   ```
2. Change into the project directory:
   ```shell
   cd weather-forecast-tool
   ```

3. Install the required dependencies:
   ```shell
   pip install requests
   ```

## Usage
1. Open the `weather_forecast.py` file in a text editor of your choice.

2. Input your OpenWeatherMap API key:
   ```python
   api_key = "YOUR_API_KEY"
   ```

   Replace `"YOUR_API_KEY"` with your own OpenWeatherMap API key. If you don't have one, you can obtain it by signing up at [OpenWeatherMap](https://home.openweathermap.org/users/sign_up).

3. Run the script:
   ```shell
   python weather_forecast.py
   ```

4. Enter the location for which you want to retrieve the weather forecast when prompted:
   ```shell
   Enter the location: London
   ```

5. The script will make a request to the OpenWeather API and display the weather information for the provided location:
   ```shell
   Weather in London:
   Temperature: 20.5°C
   Humidity: 55%
   Description: Clear sky
   ```

## Resources
- [OpenWeatherMap API Documentation](https://openweathermap.org/api)
- [Python Requests Library Documentation](https://docs.python-requests.org)
- [Python Official Website](https://www.python.org)

Feel free to customize and enhance the project according to your needs. Happy coding!
